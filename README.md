# ZH Overlay — переводчик для Deepal S07

Приложение для головного устройства Deepal: читает текст системных приложений и рисует поверх русские плашки.
Здесь публикуются готовые релизы и установщик.

## Установка

1. В машине включите отладку по USB (или по сети) и подключите её к компьютеру.
2. Скачайте установщик:
   - **Windows:** [ZhOverlay-Setup.exe](https://github.com/KozelArtem/zh-overlay-releases/releases/latest/download/ZhOverlay-Setup.exe)
   - **macOS / Linux:** [ZhOverlay-Installer.zip](https://github.com/KozelArtem/zh-overlay-releases/releases/latest/download/ZhOverlay-Installer.zip),
     распакуйте и запустите `Установить.command` (macOS) или `bash install.sh` (Linux).
3. Нажмите «Скачать» (установщик берёт последнюю версию приложения), затем «Установить».
4. Если на экране машины появится «Разрешить отладку по USB» — подтвердите и повторите.

Нужен adb: если его нет, скачайте [SDK Platform-Tools](https://developer.android.com/tools/releases/platform-tools)
и положите папку `platform-tools` рядом с установщиком.

Windows может показать «Windows защитила ваш компьютер»: файл не подписан сертификатом.
«Подробнее» → «Выполнить в любом случае».

## Обновление

Уже установленное приложение обновляется кнопкой в разделе «Настройка».

## Проверка подлинности

Все APK подписаны одним ключом, SHA-256 сертификата:
`3670c4c191a70b383562004ab1709bc9def7fa67391db5b77c88d3aeceb115fa`.
