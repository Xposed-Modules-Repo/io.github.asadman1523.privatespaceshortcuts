# Pixel Private Space Shortcuts

Natywne skróty aplikacji Przestrzeni prywatnej Pixel na ekranie głównym dzięki LSPosed.

[![Build](https://img.shields.io/github/actions/workflow/status/asadman1523/pixel-private-space-shortcuts/build.yml?branch=main&style=flat&logo=githubactions&logoColor=white)](https://github.com/asadman1523/pixel-private-space-shortcuts/actions/workflows/build.yml)
[![Release](https://img.shields.io/github/v/release/asadman1523/pixel-private-space-shortcuts?include_prereleases&style=flat&logo=github&logoColor=white)](https://github.com/asadman1523/pixel-private-space-shortcuts/releases)
[![Downloads](https://img.shields.io/github/downloads/asadman1523/pixel-private-space-shortcuts/total?style=flat&logo=github&logoColor=white)](https://github.com/asadman1523/pixel-private-space-shortcuts/releases)
[![Android](https://img.shields.io/badge/Android-17%20%2F%20API%2037%20experimental-orange?style=flat&logo=android&logoColor=white)](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.pl-PL.md#compatibility)
[![License](https://img.shields.io/badge/License-Apache--2.0-blue?style=flat&logo=apache&logoColor=white)](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/LICENSE)

Read this in other languages: [English](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/README.md), [简体中文](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.zh-CN.md), [繁體中文](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.zh-TW.md), [한국어](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.ko-KR.md), [日本語](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.ja-JP.md), **Polski**, [Français](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.fr-FR.md), [Español](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.es-ES.md), [Português](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.pt-BR.md), [Русский](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.ru-RU.md), [Türkçe](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.tr-TR.md), [Italiano](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.it-IT.md), [Bahasa Indonesia](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.id-ID.md), [Українська](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.uk-UA.md), [العربية](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.ar-AR.md), [Tiếng Việt](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.vi-VN.md), [Deutsch](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.de-DE.md), [Uzbek](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.uz-UZ.md), [עברית](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.he-IL.md)

Nagranie demonstracyjne powstanie po weryfikacji urządzenia. Symulacje nie zastępują rzeczywistych testów.

<a id="features"></a>

## Funkcje

Przytrzymaj aplikację w odblokowanej Przestrzeni prywatnej i wybierz **Dodaj do ekranu głównego** albo przeciągnij ją bezpośrednio na ekran główny. Działa to również w przypadku prywatnych aplikacji w wierszu sugestii na górze listy wszystkich aplikacji. Moduł korzysta z układu, bazy danych, ikon i kłódki Pixel Launcher. Numer seryjny profilu i komponent uruchamiania określają cel oraz zapobiegają duplikatom. Obsługiwane są przenoszenie, foldery i usuwanie.

Po zablokowaniu skrót ma zachować pozycję i wywołać uwierzytelnianie systemowe po dotknięciu. Odblokowany profil otwiera się bezpośrednio. Żądanie wykonywane jest raz, a anulowanie, przekroczenie czasu lub zniszczenie Launchera usuwa je. Nigdy nie uruchamia zastępczo kopii głównej. Zmiany dotyczą tylko elementów modułu; bez widżetów i skrótów wewnątrz aplikacji. Nazwa i ikona pozostają widoczne również po zablokowaniu.

Zablokowane skróty zachowują oryginalne kolory i natywną kłódkę. Strona informacyjna używa stałej palety czerni, bieli i szarości oraz systemowego jasnego lub ciemnego motywu.

<a id="compatibility"></a>

## Zgodność

**Eksperymentalna alfa; weryfikacja urządzenia niepełna.** Projekt skierowany na urządzenia Pixel z systemem Android 15+ (API 35+), ale **obecnie przetestowany tylko na systemie Android 17** (Pixel 10a, API 37, `CP2A.260805.005`, Pixel Launcher 17). Adapter spróbuje załadować się w systemach Android 15 i 16, ale aktualizacje mogą uszkodzić wewnętrzne hooki. Udana kompilacja nie jest dowodem zgodności.

<a id="installation"></a>

## Instalacja

Zainstaluj APK z [wydań](https://github.com/asadman1523/pixel-private-space-shortcuts/releases) w profilu głównym. Włącz **Pixel Private Space Shortcuts** w LSPosed, wybierz tylko `com.google.android.apps.nexuslauncher` i uruchom ponownie Launcher lub telefon. Testowe APK debug z CI mogą mieć inny podpis.

Strona informacyjna ma przycisk **Otwórz LSPosed**. Osobny menedżer otwiera się bezpośrednio; wbudowany wymaga pierwszej zgody Magisk. Uprawnienie jest używane tylko po naciśnięciu tego przycisku, nie do uruchamiania prywatnych aplikacji.

<a id="usage"></a>

## Użycie

Odblokuj Przestrzeń prywatną, przytrzymaj aplikację i wybierz **Dodaj do ekranu głównego** albo przeciągnij ją na ekran główny. Prywatne aplikacje w wierszu sugestii można dodać w ten sam sposób. Dotknij ikony, aby otworzyć tę samą prywatną kopię; w razie potrzeby uwierzytelnij się w Androidzie. Anulowanie porzuca żądanie. Przytrzymanie ikony pozwala przenosić, dodawać do folderu i usuwać. Ponowna próba dodania wyświetla komunikat o istniejącym skrócie. Aplikacja informacyjna modułu może służyć jako test bez danych wrażliwych w profilu prywatnym.

<a id="build"></a>

## Kompilacja

Użyj JDK 17, SDK `platforms;android-37.0`, Build Tools `36.0.0` i dołączonego wrappera Gradle. Wykonaj polecenia poniżej (`gradlew.bat` w Windows). CI kompiluje, testuje stany odblokowania, uruchamia Android lint i sprawdza wszystkie README oraz lokalne odnośniki. Cztery zmienne `PPSS_*` z [BUILDING](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/BUILDING.md) konfigurują podpis; klucze przechowuj poza repozytorium.

```sh
python3 -X utf8 tools/check_docs.py
./gradlew testDebugUnitTest lintDebug assembleDebug
```

<a id="disable"></a>

## Wyłączanie i usuwanie

Usuń zbędne skróty w Launcherze, wyłącz moduł w LSPosed i uruchom Launcher ponownie, a następnie opcjonalnie odinstaluj APK. Nie czyść danych Launchera. Istniejące elementy są natywne, lecz obsługa blokady przez moduł nie działa po wyłączeniu. Potwierdzone usunięcie aplikacji lub profilu podlega natywnemu czyszczeniu.

<a id="license"></a>

## Licencja

[Apache-2.0](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/LICENSE). Brak powiązań z Google i LSPosed. Bez dystrybucji APK Google, zdekompilowanych plików, dzienników urządzenia, danych logowania ani kluczy. Zobacz [architekturę](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/ARCHITECTURE.md) i [raport](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/TESTING.md).

[Polityka prywatności (po angielsku)](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/PRIVACY.md)
