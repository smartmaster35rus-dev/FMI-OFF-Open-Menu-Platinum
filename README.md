# Open Menu FMI-OFF Platinum

**Open Menu FMI-OFF Platinum** — настольная утилита для Windows, которая проводит iPhone/iPad через сценарий **Open Menu** и помогает снять **Find My / Activation Lock (FMI OFF)** на поддерживаемых устройствах.

Поддерживаются **все регионы iCloud**: global (**icloud.com**) и China (**icloud.com.cn**, GCBD). Программа и сервер автоматически выбирают нужный домен по региону устройства.

---

## Скачать

| | |
|---|---|
| **Последняя версия** | [**v1.0.0.25 — Releases**](https://github.com/SmartMaster35Rus/FMI-OFF-Open-Menu-Platinum/releases/latest) |
| **Установщик** | `OpenMenu_FMIOFF_Platinum_Setup.exe` (~278 MB) |
| **Платформа** | Windows 10/11 x64 |

---

## Возможности

| Функция | Описание |
|--------|----------|
| **FMI:OFF** | Open Menu: локальный прокси → Token Hunter → отправка токена на сервер |
| **USB** | Серийник, IMEI, модель, регион, версия iOS |
| **Token Hunter** | Перехват iCloud-сессии через Safari + Web Inspector |
| **Global iCloud** | icloud.com + setup.icloud.com |
| **China iCloud** | icloud.com.cn + setup.icloud.com.cn (CH/A, ZP/A …) |
| **Platinum UI** | PyQt6-лаунчер + Electron-мост, журнал, быстрые действия |
| **Erase** | Сброс устройства после успешного снятия FMI |
| **Quick actions** | Reboot, shutdown, Recovery, Fake Reset, блок OTA |
| **Языки** | Русский · English · Español |
| **Обновления** | Проверка новой версии при старте |

---

## Поддерживаемые устройства

- **iPhone / iPad**, **iOS 15.0 – 26.x**
- Подключение по **USB**, «Доверять этому компьютеру»
- Safari, **Веб-инспектор ON** (Настройки → Safari → Дополнения)

---

## Требования на ПК

- **Windows 10/11** (64-bit)
- Установка и работа **от имени администратора**
- Служба Apple Mobile Device (Apple Devices / iTunes)
- **Авторизованный серийный номер** на сервере SmartMaster35Rus

---

## Установка

1. Скачайте **`OpenMenu_FMIOFF_Platinum_Setup.exe`** из [Releases](https://github.com/SmartMaster35Rus/FMI-OFF-Open-Menu-Platinum/releases/latest)
2. Закройте предыдущие экземпляры Open Menu, если были открыты
3. Запустите установщик и следуйте мастеру
4. Запустите **Open Menu FMI-OFF Platinum** с рабочего стола или из меню «Пуск»

---

## Краткая инструкция

1. Подключите iPhone/iPad по USB, разблокируйте, нажмите **«Доверять»**
2. Нажмите **▶ Старт FMI:OFF** — дождитесь запуска прокси и охотника токена
3. На устройстве откройте **Safari** (см. таблицу ниже)
4. Выйдите из Apple ID (если уже вошли) и **войдите снова** (код-пароль / Face ID / Touch ID)
5. При запросе включите **«Режим полёта»**, затем **Продолжить** — токен уйдёт на сервер
6. Дождитесь успешного завершения на экране ПК

---

## Safari / iCloud — все регионы

| Регион | Открыть в Safari | API сервера |
|--------|------------------|-------------|
| **Global** (EU, US, RU, …) | **icloud.com** | setup.icloud.com |
| **China** (CH/A, ZP/A …) | **icloud.com.cn** | setup.icloud.com.cn |

Platinum определяет регион по USB и показывает правильную подсказку. Token Hunter перехватывает токен с обоих доменов; сервер выбирает нужный endpoint автоматически.

> На китайских устройствах **icloud.com отклонит вход** — используйте только **icloud.com.cn**.

---

## Что нового в v1.0.0.25

- **Platinum UI** — PyQt6-лаунчер, карточка устройства, журнал, быстрые действия
- **Electron-мост** — USB, локальный прокси, Token Hunter, POST токена на сервер
- **Token Hunter** — перехват iCloud-сессии через Safari + Web Inspector
- **Все регионы iCloud** — global и China, автоопределение по региону
- **Пауза перед POST** — напоминание включить «Режим полёта» перед отправкой токена
- **Проверка обновлений** при старте
- **RU / EN / ES** в интерфейсе

[Полный changelog релиза →](https://github.com/SmartMaster35Rus/FMI-OFF-Open-Menu-Platinum/releases/tag/v1.0.0.25)

---

## Поддержка

- Сайт: [smartmaster35rus.ru](https://smartmaster35rus.ru)
- Авторизация серийника и вопросы по работе — через сервис **SmartMaster35Rus**

---

**© SmartMaster35Rus · 2026**
