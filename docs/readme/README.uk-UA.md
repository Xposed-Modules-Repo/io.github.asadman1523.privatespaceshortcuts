# Pixel Private Space Shortcuts

Нативні ярлики застосунків приватного простору Pixel на головному екрані за допомогою LSPosed.

[![Build](https://img.shields.io/github/actions/workflow/status/asadman1523/pixel-private-space-shortcuts/build.yml?branch=main&style=flat&logo=githubactions&logoColor=white)](https://github.com/asadman1523/pixel-private-space-shortcuts/actions/workflows/build.yml)
[![Release](https://img.shields.io/github/v/release/asadman1523/pixel-private-space-shortcuts?include_prereleases&style=flat&logo=github&logoColor=white)](https://github.com/asadman1523/pixel-private-space-shortcuts/releases)
[![Downloads](https://img.shields.io/github/downloads/asadman1523/pixel-private-space-shortcuts/total?style=flat&logo=github&logoColor=white)](https://github.com/asadman1523/pixel-private-space-shortcuts/releases)
[![Android](https://img.shields.io/badge/Android-17%20%2F%20API%2037%20experimental-orange?style=flat&logo=android&logoColor=white)](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.uk-UA.md#compatibility)
[![License](https://img.shields.io/badge/License-Apache--2.0-blue?style=flat&logo=apache&logoColor=white)](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/LICENSE)

Read this in other languages: [English](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/README.md), [简体中文](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.zh-CN.md), [繁體中文](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.zh-TW.md), [한국어](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.ko-KR.md), [日本語](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.ja-JP.md), [Polski](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.pl-PL.md), [Français](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.fr-FR.md), [Español](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.es-ES.md), [Português](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.pt-BR.md), [Русский](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.ru-RU.md), [Türkçe](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.tr-TR.md), [Italiano](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.it-IT.md), [Bahasa Indonesia](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.id-ID.md), **Українська**, [العربية](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.ar-AR.md), [Tiếng Việt](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.vi-VN.md), [Deutsch](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.de-DE.md), [Uzbek](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.uz-UZ.md), [עברית](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.he-IL.md)

Демонстрацію буде записано після перевірки пристрою. Імітація не видається за справжні результати.

<a id="features"></a>

## Можливості

Утримуйте застосунок у розблокованому приватному просторі й виберіть **Додати на головний екран** або перетягніть його безпосередньо на головний екран. Це також працює для приватних застосунків у рядку пропозицій угорі списку всіх застосунків. Використовуються розміщення, база даних, піктограми та замок Pixel Launcher. Серійний номер профілю й компонент запуску визначають ціль і запобігають дублюванню. Підтримуються переміщення, папки та видалення.

Після блокування ярлик має зберігати позицію та запитувати системну автентифікацію. Розблокований профіль відкривається безпосередньо. Запит виконується один раз і скидається після скасування, завершення часу або знищення Launcher. Основна копія не використовується замість приватної. Змінюються лише елементи модуля; без віджетів і внутрішніх ярликів. Назва й піктограма видимі навіть у заблокованому стані.

Після блокування зберігаються початкові кольори й нативний замок. Інформаційна сторінка слідує світлій або темній темі системи зі сталою чорно-біло-сірою палітрою.

<a id="compatibility"></a>

## Сумісність

**Експериментальна альфа; перевірку пристрою не завершено.** Орієнтовано на пристрої Pixel з Android 15+ (API 35+), але **наразі протестовано лише на Android 17** (Pixel 10a, API 37, `CP2A.260805.005`, Pixel Launcher 17). Адаптер спробує завантажитися на Android 15 та 16, але оновлення можуть порушити роботу внутрішніх хуків. Успішна збірка не є доказом сумісності.

<a id="installation"></a>

## Встановлення

Встановіть APK із [випусків](https://github.com/asadman1523/pixel-private-space-shortcuts/releases) в основний профіль. У LSPosed увімкніть **Pixel Private Space Shortcuts**, виберіть лише `com.google.android.apps.nexuslauncher`, перезапустіть Launcher або телефон. Тестові debug APK з CI можуть мати інший підпис.

Сторінка має кнопку **Відкрити LSPosed**. Окремий менеджер відкривається безпосередньо; вбудований уперше потребує дозволу Magisk. Дозвіл використовується лише для цієї кнопки, не для запуску приватних застосунків.

<a id="usage"></a>

## Використання

Розблокуйте приватний простір, утримуйте застосунок і виберіть **Додати на головний екран** або перетягніть його на головний екран. Приватні застосунки з рядка пропозицій можна додати так само. Натискання відкриває ту саму приватну копію; за потреби пройдіть перевірку Android. Скасування відхиляє запит. Утримуйте піктограму для переміщення, папки або видалення. Повторне додавання повідомляє про наявний ярлик. Інформаційний застосунок модуля можна встановити в приватному просторі як тест без чутливих даних.

<a id="build"></a>

## Збірка

Використовуйте JDK 17, SDK `platforms;android-37.0`, Build Tools `36.0.0` і наданий Gradle wrapper. Виконайте команди нижче (`gradlew.bat` у Windows). CI збирає, тестує стани розблокування, запускає Android lint і перевіряє всі README та локальні посилання. Чотири змінні `PPSS_*` з [BUILDING](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/BUILDING.md) налаштовують підпис; ключі зберігайте поза репозиторієм.

```sh
python3 -X utf8 tools/check_docs.py
./gradlew testDebugUnitTest lintDebug assembleDebug
```

<a id="disable"></a>

## Вимкнення й видалення

Видаліть непотрібні ярлики через Launcher, вимкніть модуль у LSPosed і перезапустіть Launcher; після цього можна видалити APK. Не очищуйте дані Launcher. Наявні елементи нативні, але обробка блокування модулем буде недоступна. Підтверджене видалення застосунку або профілю використовує штатне очищення.

<a id="license"></a>

## Ліцензія

[Apache-2.0](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/LICENSE). Без зв’язку з Google або LSPosed. APK Google, декомпільовані файли, журнали пристрою, облікові дані та ключі не поширюються. Див. [архітектуру](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/ARCHITECTURE.md) й [перевірки](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/TESTING.md).

[Політика конфіденційності (англійською)](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/PRIVACY.md)
