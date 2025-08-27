# 🌟 Dynamic AOD Wallpapers (OneUI)

> **Включите скрытую функцию динамических обоев на Samsung A55!**

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/mikhailfur/DynamicAODWallpapers)
[![Platform](https://img.shields.io/badge/platform-Android-green.svg)](https://www.android.com/)
[![OneUI](https://img.shields.io/badge/OneUI-6.0+-orange.svg)](https://www.samsung.com/global/galaxy/one-ui/)
[![Device](https://img.shields.io/badge/device-Samsung%20A55-red.svg)](https://www.samsung.com/global/galaxy/galaxy-a55/)

## 📱 Описание

**Dynamic AOD Wallpapers** - это Magisk/KernelSU модуль, который активирует скрытую функцию динамических обоев Always On Display на устройствах Samsung с OneUI. Модуль заменяет системный файл `floating_feature.xml`, чтобы разблокировать возможность использования динамических обоев в режиме AOD.

## ✨ Возможности

- 🔓 **Разблокировка скрытых функций** - активация динамических обоев AOD
- 🎨 **Динамические обои** - поддержка анимированных фонов в Always On Display
- 🔄 **Автоматическое резервирование** - создание бэкапа оригинального файла
- 🛡️ **Безопасная установка** - проверка совместимости и откат изменений
- 📱 **OneUI оптимизация** - специально для Samsung Galaxy A55

## 📋 Требования

- **Устройство:** Samsung Galaxy A55
- **Android:** OneUI 6.0+
- **Root:** Magisk или KernelSU
- **Версия:** Android 14+

## 🚀 Установка

### Способ 1: Через Magisk Manager

1. Скачайте последнюю версию модуля
2. Откройте Magisk Manager
3. Перейдите в раздел "Модули"
4. Нажмите "Установить из ZIP"
5. Выберите скачанный файл
6. Перезагрузите устройство

### Способ 2: Через KernelSU

1. Скачайте последнюю версию модуля
2. Откройте KernelSU Manager
3. Перейдите в раздел "Модули"
4. Нажмите "Установить"
5. Выберите скачанный файл
6. Перезагрузите устройство

### Способ 3: Через Recovery

1. Скачайте модуль на устройство
2. Перезагрузитесь в Recovery
3. Установите ZIP файл
4. Перезагрузитесь

## 🔧 Настройка

После установки модуля:

1. Перезагрузите устройство
2. Откройте **Настройки** → **Экран блокировки**
3. Выберите **Always On Display**
4. Настройте **Обои AOD**
5. Выберите динамические обои

## 📁 Структура модуля

```
DynamicAODWallpapers/
├── META-INF/
│   └── com/google/android/
│       ├── update-binary
│       └── updater-script
├── system/
│   └── etc/
│       └── floating_feature.xml
├── customize.sh
├── module.prop
├── uninstall.sh
└── README.md
```

## 🛠️ Технические детали

Модуль работает путем замены системного файла `floating_feature.xml`, который содержит конфигурацию функций OneUI. При установке:

- Создается резервная копия оригинального файла
- Устанавливается модифицированная версия
- Настраиваются правильные права доступа
- При удалении модуля восстанавливается оригинал

## ⚠️ Важные замечания

- **Только для Samsung A55** - не тестировался на других устройствах
- **Создавайте резервные копии** важных данных перед установкой
- **Не удаляйте модуль** во время использования динамических обоев
- **Проверяйте совместимость** с вашей версией OneUI

## 🔄 Удаление

### Через Magisk/KernelSU Manager

1. Откройте менеджер модулей
2. Найдите "Dynamic AOD Wallpapers"
3. Нажмите "Удалить"
4. Перезагрузите устройство

### Автоматическое восстановление

При удалении модуля автоматически восстанавливается оригинальный файл `floating_feature.xml` из резервной копии.

## 🐛 Устранение неполадок

### Проблема: Модуль не устанавливается

- Убедитесь, что у вас есть root права
- Проверьте совместимость с вашей версией Magisk/KernelSU
- Попробуйте переустановить Magisk/KernelSU

### Проблема: Динамические обои не работают

- Перезагрузите устройство после установки
- Проверьте настройки Always On Display
- Убедитесь, что выбраны динамические обои

### Проблема: Устройство не загружается

- Загрузитесь в Safe Mode
- Удалите модуль через Recovery
- Восстановите из резервной копии

## 📞 Поддержка

Если у вас возникли проблемы или есть предложения:

- 📧 **Issues:** [GitHub Issues](https://github.com/mikhailfur/DynamicAODWallpapers/issues)
- 💬 **Telegram:** [@dataisnotfound](https://t.me/dataisnotfound)
- 📱 **Discord:** Присоединяйтесь к нашему серверу

## 📄 Лицензия

Этот проект распространяется под лицензией [MIT License](LICENSE).

## 🙏 Благодарности

- Команде **Magisk** за отличную систему модулей
- Команде **KernelSU** за альтернативное решение
- Сообществу **Samsung** за вдохновение
- Всем **тестерам** и **контрибьюторам**

## 📊 Статистика

![GitHub stars](https://img.shields.io/github/stars/mikhailfur/DynamicAODWallpapers?style=social)
![GitHub forks](https://img.shields.io/github/forks/mikhailfur/DynamicAODWallpapers?style=social)
![GitHub issues](https://img.shields.io/github/issues/mikhailfur/DynamicAODWallpapers)
![GitHub pull requests](https://img.shields.io/github/issues-pr/mikhailfur/DynamicAODWallpapers)

---

<div align="center">
  <p><strong>⭐ Не забудьте поставить звездочку, если модуль вам понравился!</strong></p>
  <p>Сделано с ❤️ для сообщества Samsung</p>
</div>
