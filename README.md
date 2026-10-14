# יציב - ביטוח נסיעות לחו"ל

דף נחיתה סטטי (קובץ HTML יחיד, ללא תלות בשרת) עם השוואת מחירי ביטוח נסיעות.

## העלאה ל-GitHub Pages
1. צרו מאגר (repository) חדש ב-GitHub.
2. העלו את `index.html` ו-`README.md` לענף `main`.
3. Settings > Pages > Source: Deploy from a branch > `main` / root > Save.
4. האתר יעלה בכתובת `https://USERNAME.github.io/REPO/`.

## עדכון תעריפים וקישורים
ב-`index.html` חפשו את `var COMPANIES=` ועדכנו לכל חברה:
- `daily` - תעריף יומי בדולרים לנוסע עד גיל 60
- `url` - קישור לרכישה (`null` מסתיר את הכפתור)
- `badge` / `perk` - הטבות

## הערות
- טופס ההצעה מחשב השוואה בלבד ואינו שולח פרטים לשום שרת.
- התמונות והלוגו מוטמעים בתוך הקובץ.
