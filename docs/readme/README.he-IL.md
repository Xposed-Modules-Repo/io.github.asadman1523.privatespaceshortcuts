# Pixel Private Space Shortcuts

קיצורי דרך מקוריים במסך הבית לאפליקציות המרחב הפרטי ב־Pixel, באמצעות LSPosed.

[![Build](https://img.shields.io/github/actions/workflow/status/asadman1523/pixel-private-space-shortcuts/build.yml?branch=main&style=flat&logo=githubactions&logoColor=white)](https://github.com/asadman1523/pixel-private-space-shortcuts/actions/workflows/build.yml)
[![Release](https://img.shields.io/github/v/release/asadman1523/pixel-private-space-shortcuts?include_prereleases&style=flat&logo=github&logoColor=white)](https://github.com/asadman1523/pixel-private-space-shortcuts/releases)
[![Downloads](https://img.shields.io/github/downloads/asadman1523/pixel-private-space-shortcuts/total?style=flat&logo=github&logoColor=white)](https://github.com/asadman1523/pixel-private-space-shortcuts/releases)
[![Android](https://img.shields.io/badge/Android-17%20%2F%20API%2037%20experimental-orange?style=flat&logo=android&logoColor=white)](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.he-IL.md#compatibility)
[![License](https://img.shields.io/badge/License-Apache--2.0-blue?style=flat&logo=apache&logoColor=white)](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/LICENSE)

Read this in other languages: [English](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/README.md), [简体中文](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.zh-CN.md), [繁體中文](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.zh-TW.md), [한국어](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.ko-KR.md), [日本語](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.ja-JP.md), [Polski](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.pl-PL.md), [Français](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.fr-FR.md), [Español](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.es-ES.md), [Português](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.pt-BR.md), [Русский](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.ru-RU.md), [Türkçe](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.tr-TR.md), [Italiano](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.it-IT.md), [Bahasa Indonesia](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.id-ID.md), [Українська](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.uk-UA.md), [العربية](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.ar-AR.md), [Tiếng Việt](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.vi-VN.md), [Deutsch](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.de-DE.md), [Uzbek](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/readme/README.uz-UZ.md), **עברית**

ההדגמה תוקלט לאחר בדיקה במכשיר. הדמיה לא תוצג כתוצאת בדיקה אמיתית.

<a id="features"></a>

## תכונות

לחצו לחיצה ארוכה על אפליקציה במרחב פרטי פתוח ובחרו **הוספה למסך הבית**, או גררו אותה ישירות למסך הבית. זה עובד גם עבור אפליקציות פרטיות המוצגות בשורת ההצעות בראש כל האפליקציות. המודול משתמש במיקום, במסד הנתונים, בסמלים ובסימון המנעול של Pixel Launcher. המספר הסידורי של הפרופיל ורכיב ההפעלה מזהים את היעד ומונעים כפילויות. נתמכים הזזה, תיקיות והסרה.

בעת נעילה קיצור הדרך נועד לשמור על מיקומו ולבקש אימות מערכת בלחיצה. כשהמרחב פתוח, העותק הפרטי נפתח ישירות. הבקשה מתבצעת פעם אחת ונמחקת בביטול, בתום הזמן או בהשמדת Launcher. אין מעבר חלופי לעותק הראשי. רק פריטים שהמודול יצר משתנים; ללא ווידג׳טים או קיצורים פנימיים. שם האפליקציה והסמל גלויים גם בזמן נעילה.

קיצורים נעולים שומרים על הצבעים המקוריים ועל סימון המנעול. דף המידע מתאים למצב הבהיר או הכהה של המערכת בצבעי שחור, לבן ואפור קבועים.

<a id="compatibility"></a>

## תאימות

**גרסת אלפא ניסיונית; בדיקת המכשיר אינה מלאה.** מיועד למכשירי Pixel עם Android 15+ (API 35+), אך **נבדק כרגע רק ב־Android 17** (Pixel 10a, API 37, `CP2A.260805.005`, Pixel Launcher 17). המתאם ינסה להיטען ב־Android 15 ו־16, אך עדכונים עלולים לשבור hooks פנימיים. בנייה מוצלחת אינה מוכיחה תאימות.

<a id="installation"></a>

## התקנה

התקינו את APK מ[ההפצות](https://github.com/asadman1523/pixel-private-space-shortcuts/releases) בפרופיל הראשי. הפעילו **Pixel Private Space Shortcuts** ב־LSPosed, בחרו רק `com.google.android.apps.nexuslauncher` והפעילו מחדש את Launcher או את הטלפון. קובצי debug מ־CI מיועדים לבדיקה ועשויים לשאת חתימה שונה.

בדף יש כפתור **פתיחת LSPosed**. מנהל נפרד נפתח ישירות; המנהל המובנה דורש אישור Magisk בפעם הראשונה. ההרשאה משמשת רק בלחיצה על הכפתור, ולא לפתיחת אפליקציות פרטיות.

<a id="usage"></a>

## שימוש

פתחו את המרחב הפרטי, לחצו ארוכות על אפליקציה ובחרו **הוספה למסך הבית**, או גררו אותה למסך הבית. אפשר להוסיף באותו אופן גם אפליקציות פרטיות משורת ההצעות. לחיצה על הסמל פותחת את אותו עותק פרטי; בצעו אימות דרך Android לפי הצורך. ביטול משליך את הבקשה. לחיצה ארוכה מאפשרת הזזה, הכנסה לתיקייה או הסרה. הוספה חוזרת מודיעה שהקיצור קיים. אפשר להתקין את אפליקציית המידע של המודול במרחב הפרטי לבדיקה ללא מידע רגיש.

<a id="build"></a>

## בנייה

השתמשו ב־JDK 17, ב־SDK `platforms;android-37.0`, ב־Build Tools `36.0.0` וב־Gradle wrapper הכלול. הריצו את הפקודות להלן (`gradlew.bat` ב־Windows). CI בונה, בודק מצבי פתיחת נעילה, מריץ Android lint ובודק את כל קובצי README והקישורים המקומיים. ארבעת משתני `PPSS_*` ב[BUILDING](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/BUILDING.md) מגדירים חתימה; שמרו מפתחות מחוץ למאגר.

```sh
python3 -X utf8 tools/check_docs.py
./gradlew testDebugUnitTest lintDebug assembleDebug
```

<a id="disable"></a>

## השבתה או הסרה

הסירו קיצורים לא רצויים דרך Launcher, השביתו את המודול ב־LSPosed והפעילו מחדש את Launcher; לאחר מכן אפשר להסיר את APK. אל תמחקו את נתוני Launcher. הפריטים קיימים כפריטים מקוריים, אך טיפול הנעילה של המודול אינו זמין כשהוא מושבת. מחיקה מאומתת של אפליקציה או פרופיל משתמשת בניקוי המקורי.

<a id="license"></a>

## רישיון

[Apache-2.0](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/LICENSE). ללא קשר ל־Google או ל־LSPosed. אין הפצת APK של Google, קבצים שעברו פירוק, יומני מכשיר, פרטי אימות או מפתחות. ראו [ארכיטקטורה](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/ARCHITECTURE.md) ו[בדיקות](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/docs/TESTING.md).

[מדיניות פרטיות (באנגלית)](https://github.com/Xposed-Modules-Repo/io.github.asadman1523.privatespaceshortcuts/blob/main/PRIVACY.md)
