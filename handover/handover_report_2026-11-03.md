# Zeny Empire – דוח העברת מצב (3/11/2026, עודכן 11:35 שעון ישראל, אחרי תיקון הבאגים)

הוכן על ידי Claude לפי בקשת אושר, לקראת חלוקת אחריות חדשה:
- **ChatGPT:** ניהול עסקי, אסטרטגיה ומחירים.
- **Claude:** מלאי, איסוף נתוני שוק ופיתוח האתר.

הדוח הוכן בלי לשנות שום דבר במערכת. ב-11:30 אושר אישר לתקן את הבאגים שנמצאו (פירוט בסעיף 9). לפני התיקון נשמר גיבוי מלא: `zeny-empire/backup-before-fixes-2026-11-03.json`.

**מקרא לרמת הוודאות:**
- **[מאומת]** – נראה בצילום מסך של אושר או שאושר אמר במפורש.
- **[רישום]** – כך כתוב במסד הנתונים, אבל לא נבדק היום.
- **[לא ידוע]** – אין נתון.

שרת: iRO Renewal – Chaos. אזור זמן: ישראל (UTC+2). האיפוס היומי במשחק ב-13:00.

---

## 1. יתרות זני

| דמות | חשבון | תפקיד | זני | מתי ומקור |
|---|---|---|---|---|
| Cuteanddeadly | oshen11 | ראשית, Windhawk 247 | 398,260,243 | מצילום 2/11; אושר 3/11 11:25: לא התחברה מאז, לא השתנה [מאומת על ידי אושר] |
| CutesellsWoman | oshen11 | מרצ'נט ראשי וקופה | 91,924,117 | 3/11 ~10:25 [מאומת], אחרי 3 קניות הבוקר |
| ZenyEmpire | OsherFederma | מרצ'נט משני | 492,420,690 | 3/11 11:24 [מאומת בצילום] |
| buffsareus | oshen11 | Arch Bishop 146, באפר | 1,488,616 | אושר 3/11 11:26: לא השתנה מהצילום של 2/11 [מאומת על ידי אושר] |
| LoveBubbles | BenFederman | מרצ'נט שלישי (Job 19) | 6,349,914 | 3/11 10:39 [מאומת בצילום] |
| LoveClover | agam25 | Novice באימון ל-Merchant | [לא ידוע] | קיבלה כ-500,000 מ-LoveBubbles ב-3/11 [לא מאומת] |
| **סה"כ ידוע** | | | **990,443,580** | בלי LoveClover |

הערות:
- `settings/main` עודכן (תיקון 3/11 11:30): liquid = 990,443,580. ל-LoveClover עדיין אין יתרה, והאתר מציג אצלה "לא ידוע".
- תקרת זני לדמות לפי iRO Wiki: 2,147,483,647.

## 2. מלאי

המסד מכיל 796 רשומות. הבסיס הוא ספירה מלאה מצילומי מסך מ-2/11, עם עדכונים עד 3/11 11:30. הקובץ המלא: `inventory_db_2026-11-03.csv` (בתיקייה הזו).

| דמות | מיקום | רשומות |
|---|---|---|
| Cuteanddeadly* | מחסן Kafra (ראשי ומשני, משותף לחשבון oshen11) | 535 |
| Cuteanddeadly* | מחסן גילדה (Guild Of Love, משותף לכל הדמויות) | 74 |
| Cuteanddeadly | על הדמות / תיק | 20 / 34 |
| CutesellsWoman | חנות (רגילה 12 + מוכר פרטי 4) | 16 |
| CutesellsWoman | תיק / על הדמות | 30 / 2 |
| ZenyEmpire | חנות / תיק / על הדמות | 12 / 15 / 3 |
| LoveBubbles | חנות | 12 |
| LoveClover | תיק (Bat Von Blood) | 1 |
| buffsareus | מחסן Kafra / תיק / על הדמות | 37 / 2 / 2 |

\* מחסנים משותפים נרשמו תחת Cuteanddeadly, אבל בפועל כל דמות בחשבון oshen11 ניגשת למחסן הראשי, וכל דמות בגילדה ניגשת למחסן הגילדה.

**סטטוסים במסד:**

| סטטוס | רשומות |
|---|---|
| להשאיר | 350 |
| להשתמש | 211 |
| לבדוק מחיר | 184 |
| למכור | 47 |
| נמכר | 4 |

**עלות קנייה רשומה ל-6 פריטים:**
- Kshatra +13: 14,999,999
- Bat Von Blood: 17,990,000
- Dame of Sentinel Card: 1,900,000
- Cherry Blossom: 14,444,444
- Footprints: 3,000,000
- Premium Box: 33,999,998

**פריטים בחנויות:** כל פריט בחנות מסומן במסד כ-`loc=חנות`, יחד עם `shop` של החנות ו-`price` שהוא המחיר המפורסם.

## 3. פריטים למכירה ופריטים לשמירה

**לשמור (מוגן, לא למכירה):**
- כל הציוד שלבוש על Cuteanddeadly (Windhawk):
  - +14 Moonflower Bow
  - סט Master Shadow + Gale Shadow
  - +13 Kshatra Vairya of Keen
  - +14 Focused Cat Paw
  - +13 Screaming Ghost Party
  - +14 Royal Prontera Cape
  - Focused Hatred/Love Ring
  - Dim Glacier Follower
  - Moon God Lapel
  - קוסטיומים: Tiara, Heart Angel, Lovely Feeling, Samba Carnival Feather
  - Silver Arrow
- ציוד לאחרי הלבלינג, במחסן Kafra: +13 Invincible Crest Hat, Icarus Gloves of Void, +12 Ancient Mechanic Greaves.
- ערכת לבלינג לדמויות חדשות, במחסן הגילדה: Costume Goggles ×2 (+30% EXP), Under a Cast Clip [Phen].
- buffsareus: +9 Miraculous Shrine Maiden Hat [Arc Angeling], +12 Adoramus Holy Stick.
- Bloody Branch (בתיק של Cuteanddeadly).
- נקנו הבוקר לשימוש אישי: Costume Fluttering Cherry Blossom, Cherry Blossom Footprints, [10 Days] Premium Subscription Box. ה-Premium Box ממתין להפעלה (ראו סעיף 9).
- Bat Von Blood: לפי המסד "לשמור", כציוד לבלינג. בפועל הועבר מ-LoveBubbles ל-LoveClover בטרייד ב-3/11.

**למכירה:**
- כל מה שבחנויות (סעיף 5).
- פריטים שסומנו "למכור" ואינם בחנות:
  - +12 Illusion Armor Type A
  - +9 Immune Erymanthian Skin [Raydric]
  - Peerless Ancient Morocc Jewelry. **לא נמצא במשחק לפי אושר.**
  - Mr. Scream ×4
  - Dreaming Red Sheep. כן נמצא בחנות של ZenyEmpire.
  - Variant Shoes ×2. **לא נמצאו במחסן הגילדה (אושר, 3/11).**
  - Roost of Skelion
  - Abysmal Knight Card ×2
  - Dame of Sentinel Card
- **מיון מחסנים מ-3/11** (`cleanup_2026-11-03.md`):

  | קבוצה | שורות | שווי משוער |
  |---|---|---|
  | A – למכירה לשחקנים | 142 | כ-54.4M (בעיקר חומרים) |
  | B – ל-NPC | 187 | כ-2.56M |
  | C – לשמור | 23 | – |
  | D – ציוד וקלפים שלא נבדקו בשוק | 317 | – |

  המיון הזה הוא הצעה בלבד ולא בוצע.

## 4. עסקאות אחרונות (כל מה שנרשם, 2–3/11)

| תאריך ושעה (ישראל) | סוג | פריט | מחיר | דמות | צד שני |
|---|---|---|---|---|---|
| 2/11 16:34 | מכירה | Gan Ceann Card | 3,500,000 | ZenyEmpire | KinsonLau |
| 2/11 18:23 | קנייה (להיפוך) | +13 Kshatra Vairya [1] Agi+15/Atk+47 | 14,999,999 | CutesellsWoman | Renkuriel |
| 2/11 18:49 | מכירה | Moon Follower Eyepatch | 8,500,000 | ZenyEmpire | Sahak~Mahadik |
| 2/11 21:03 | מכירה | Wandering Duck Doll Egg | 1,200,000 | ZenyEmpire | לא ידוע |
| 2/11 21:55 | קנייה (ציוד לבלינג) | Bat Von Blood | 17,990,000 | ZenyEmpire | BVB |
| 3/11 10:16 | קנייה (אישי) | Costume Fluttering Cherry Blossom | 14,444,444 | CutesellsWoman | Anya Passing |
| 3/11 10:19 | מכירה | +12 Double Kingbird Big Crossbow [2x Archer Skeleton] | 5,900,000 | LoveBubbles | OnlineZenyMaster |
| 3/11 10:20 | קנייה (אישי) | Cherry Blossom Footprints | 3,000,000 | CutesellsWoman | לא ידוע |
| 3/11 10:23 | קנייה (VIP) | [10 Days] Premium Subscription Box | 33,999,998 | CutesellsWoman | חנות "Sale!!" |

- סה"כ מכירות: 19,100,000. אף מכירה לא הייתה מעל 10M, ולכן לא שולם מס.
- סה"כ קניות: 84,434,441. מתוכן רק Kshatra נועדה לעסק (להיפוך). השאר נועדו לשימוש.
- לאף אחת מהמכירות אין עלות רשומה, ולכן הרווח שלהן לא ידוע.
- מכירות קודמות ל-2/11 לא נרשמו. ב-2/11 אושר הורה "מתחילים מ-0".

## 5. מצב החנויות והמחירים המפורסמים

כל החנויות נמצאות בפרונטרה. המחירים הם מחירים מבוקשים, לא עסקאות.

**A. LoveBubbles – Vending**
- נפתחה מחדש ב-3/11 10:47, מאומת בצילום.
- שם החנות: `Valkyrie Drop x2 | VBow+12 CHEAP`

| # | פריט | מחיר |
|---|---|---|
| 1 | +12 Queenbird Heavy Blade Virtual Bow-OS | 139,900,000 |
| 2 | Aqua Benedict Valkyrie Drop | 94,900,000 |
| 3 | Valkyrie Drop of Mad Witch | 89,900,000 |
| 4 | Angeling Egg | 49,900,000 |
| 5 | +9 Holy Antonio's Coat [Angeling] | 19,900,000 |
| 6 | Happy Balloon | 8,900,000 |
| 7 | White Bird Rose | 7,900,000 |
| 8 | +13 White Wing Suit of Agility Switching [Ancient Mimic] | 7,900,000 |
| 9 | Costume Crown | 5,499,000 |
| 10 | +12 Hunter Bow | 4,900,000 |
| 11 | Coral Reef ×376 | 9,999 ליח' |
| 12 | Costume Ribbon Hat | 249,000 |

זני בפתיחה: 6,349,914. מכירה תזוהה לפי עלייה מהסכום הזה.

**B. CutesellsWoman – Vending**
- נפתחה מחדש ב-3/11 11:04, מאומת בצילום.
- שם החנות: `Jumbo Rabbit | Kshatra+13 | Crimson+`
- המחירים נקבעו לפי iromarket (3/11 06:43), מעט מתחת לשוק, באישור אושר.

| # | פריט | מחיר |
|---|---|---|
| 1 | Costume Jumbo Rabbit (Shrink Effect) | 229,900,000 |
| 2 | +13 Kshatra Vairya (Agi+15/Atk+47) | 13,299,999 (מחיר הקנייה היה 14,999,999) |
| 3 | +15 Double Malicious Crimson Bow [2x Hunter Fly] | 49,000,000 (בחירת אושר, אין מכירות של +15) |
| 4 | Magical Booster | 18,900,000 |
| 5 | +9 Peerless Autumn Headband | 9,900,000 |
| 6 | Demon's Familiar [1] | 9,500,000 |
| 7 | Kick Step Card | 5,900,000 |
| 8 | Book of Death Card | 4,900,000 |
| 9 | Brutal Murderer Card | 2,900,000 |
| 10 | True Hunting Ring | 2,900,000 |
| 11 | Costume Burning Cloak | 27,900,000 |
| 12 | Beloved Mastering Egg | 2,500,000 |

זני בפתיחה: 91,924,117.

**C. CutesellsWoman – מוכר פרטי (Consignment, Offline Voucher Lv2)**
- [רישום] נפתח 3/11 00:00. תוקף משוער עד 12/11 (לא מאומת).

| פריט | מחיר |
|---|---|
| +9 Penetration Shadow Pendant | 89,900,000 |
| +12 Ignis Cap Type K of Archer (Dolomedes) | 79,900,000 |
| +13 Orb of Deprave Evil Dragon Armor | 59,000,000 |
| +9 Penetration Shadow Earring | 45,000,000 |

**D. ZenyEmpire – Vending**
- [רישום] נפתחה 2/11 22:08. לא נבדק היום.
- שם החנות: `LOYAL Orc Hero Egg | Angel Wings`

| פריט | מחיר |
|---|---|
| Costume Angel Wings | 249,900,000 |
| Dreaming Red Sheep | 189,900,000 |
| Orc Hero Egg (Loyal) | 89,900,000 |
| Costume Fluffy Lovely Fox | 9,900,000 |
| +10 Arrow Shadow Armor | 8,900,000 |
| +9 Arrow Shadow Shield | 7,700,000 |
| +9 Arrow Shadow Shoes | 7,500,000 |
| Solid Rod ×2 | 4,900,000 כל אחד |
| +11 White Wing Manteau | 4,900,000 |
| Abysmal Knight Card ×2 | 3,300,000 |
| Window Shopper Catalogue ×47 | 59,999 |

## 6. מבנה מאגר הנתונים וקובצי הפרויקט

**האתר (מקור האמת):**
- כתובת: https://claude.ai/artifact/TYcXBrk3GzaNTtcz2kKQBx
- גרסה 21, פורסמה 1/11. מאז השתנו רק נתונים, לא קוד.
- הנתונים נשמרים במסד של claude.ai (ArtifactData), ולכן רק Claude ואושר ניגשים אליהם ישירות.
- ייצוא מלא של המסד: `db_export_2026-11-03.json` (בתיקייה הזו).

| אוסף | רשומות | שדות עיקריים |
|---|---|---|
| settings/main | 1 | liquid, reserve (100M), dealCap (200M), zeny{דמות:{v,at}}, zcap, thr |
| characters | 6 | name, acc, cls, blv, jlv, role, ctype, active |
| items | 796 | name, refine, card, qty, char, loc, cat, status, keep, shop, price, cost, mkt, npc, notes |
| shops | 4 | char, kind, title, listing[{n,p}], sold[], openedAt, zenyBase, active |
| trades | 9 | ראו הבאג בסעיף 9 |
| snapshots | 1 | 2026-11-01 |
| transfers, market | 0 | ריקים. 16 רשומות market נמחקו לבקשת אושר ב-2/11 |

**תיקיית הפרויקט** (`/mnt/project-files/`, נגישה ל-Claude):

| נתיב | תוכן |
|---|---|
| `zeny-empire/strategy.md` | מסמך האסטרטגיה המקורי של ChatGPT מ-2/11 |
| `inventory/count_2026-11-02.csv` | ספירת המלאי הגולמית, עם 4 גיבויים .bak |
| `zeny-empire/market/` | סריקות iromarket: 2/11 (474 שורות), חומרים, פריטים יקרים, מחירים מ-3/11, בדיקת חנויות 3/11 |
| `zeny-empire/cleanup_2026-11-03.md` | מיון מחסנים |
| `zeny-empire/zeny-empire-v21.html` | קוד האתר |
| `zeny-empire/backup-*` | גיבויים |
| `money/תוכנית_זני_700M.md` | תוכנית זני מ-1/11 |

**במחשב של אושר:** `C:\Users\Stock Surfer\Desktop\ZenyEmpire\`
- `market\`: סריקות וקובצי מיקומי חנויות מ-3/11.
- `backups\2026-11-02`.

**GitHub (ציבורי):**
- github.com/benfederman1-svg/zeny-empire-data
- הקבצים summary.txt, data.json ו-index.html הם תמונת מצב מ-2/11 ולא מתעדכנים לבד.

## 7. נוסחאות והנחות (מתוך הקוד של v21)

- **מס דוכן:** `vendTax(p) = p > 10,000,000 ? round(0.05 × p) : 0`. בטרייד אין מס.
- **רווח ממכירה:** `profit = total − tax − cost`. כשאין עלות, הרווח null ("לא ידוע") ולא נספר בסיכומים.
- **רווח ממומש:** סכום הרווח של מכירות שאינן חיצוניות ושיש להן עלות.
- **הון כולל:** `liquid + עלות מלאי מסחר`. פריטים שמסומנים לשמור/להשתמש נספרים ב-0.
- **שווי שוק משוער (EMV):** `liquid + Σ(vendNet(מחיר שוק טרי) × כמות)`. כרגע אין מחירי שוק במסד, ולכן הערך הוא 0.
- **תקציב עסקה:** `max(0, min(dealCap, liquid − reserve))`. כלומר `min(200M, liquid − 100M)`.
- **קנייה:** מוסיפה למלאי עם עלות ממוצעת משוקללת. העברה בין דמויות אינה רווח ואינה הוצאה.
- **סורק:** ROI מתחת ל-5% מסומן AVOID. בלי מספיק נתונים הפריט עובר ל-Watchlist ולא מסומן BUY.
- **תקרת זני לדמות:** 2,147,483,647. ספי התראה: 70% / 85% / 95%.
- **הנחות שאינן בקוד (מהעבודה עד היום):**
  - יעד רווח לעסקה: 10–15M נטו.
  - מחיר מינימום לפריט בחנות: כ-1.5–2M.
  - אושר מעדיף מחזור מהיר על פני מחיר מקסימלי.
  - פריט מעל 10M עדיף למכור בטרייד.

## 8. מקורות לסריקות שוק

- **iromarket.net:** המקור היחיד לנתונים חיים של Chaos.
  - דורש התחברות עם Discord, ולכן Claude נכנס אליו דרך המחשב של אושר (Remote Control + Chrome, קריאה בלבד).
  - נותן מוכרים, מחירים, כמויות ומיקום חנות, וגם היסטוריה של כ-10 ימים (מכירות שמוסקות מירידה במלאי).
  - **מגבלות:** הקואורדינטות לא תמיד נכונות. ב-3/11 izlude 135/148 התגלה כשגוי. ההיסטוריה מראה מכירות "מוסקות" ולא עסקאות מאומתות, ואנצ'נטים לא תמיד מוצגים. החנויות של אושר עצמו מופיעות שם באיחור, ולכן אין להשתמש בהן כמחיר שוק.
- **לוחות מסחר במשחק:**
  - מאומתים: פרונטרה 160/189 ו-146/80, פייאון 183/99. אין לוח באיזלוד.
  - כל לוח מחפש רק בעיר שלו.
- **Window Shopper Catalogue:** חיפוש חנויות בתוך המשחק.
- **דיסקורד iRO Chaos Market:** נקרא רק כשאושר מבקש. בערוץ #statistics יש הודעה אחת שמתעדכנת, בלי היסטוריה.
- **iRO Wiki / divine-pride:** מידע על פריטים ומפות.
- **לא בשימוש:** RagnaStats, כי הנתונים שם מ-2019 ולא מ-Chaos.

## 9. משימות פתוחות, באגים ובעיות ידועות

**תוקן ב-3/11 11:30, באישור אושר.** לפני התיקון נשמר גיבוי. לא נמחקה אף רשומה, ולא נמחק אף שדה ישן.

1. **פורמט עסקאות.** לכל 9 העסקאות נוספו השדות שהאתר קורא: `d, item, itemId, qty, side, unit, total, tax, cost, profit, ch, act, zc, party, external, ts`.
   - בקניות: `cost` = המחיר ששולם, `profit` = 0.
   - במכירות: `cost` ו-`profit` נשארו null, כי לא ידוע כמה עלה הפריט.
   - השדות הישנים נשמרו.
2. **שיוך לחנויות.** 40 פריטים קיבלו `loc=חנות`, את ה-`shop` שלהם ואת המחיר המפורסם:

   | חנות | פריטים |
   |---|---|
   | LoveBubbles | 12 |
   | CutesellsWoman | 12 |
   | מוכר פרטי | 4 |
   | ZenyEmpire | 12 |

   - הפריטים עברו לדמות שמוכרת אותם. הדמות והמיקום הקודמים נשמרו בהערה של כל פריט.
   - Costume Burning Cloak רשום בתיק של ZenyEmpire, אבל בצילום הוא בחנות של CutesellsWoman.
3. **פריטים שנמכרו וסומנו נמכר (כמות 0):** Big Crossbow (i05), Wandering Duck Doll Egg (i26), Gan Ceann Card (n238).
4. **רשומות חדשות:**
   - Costume Crown (היה בספירה וחסר במסד).
   - Window Shopper Catalogue: 47 יחידות בחנות ZenyEmpire ו-52 בתיק. הפיצול לא מאומת.
   - 3 הקניות של הבוקר: Cherry Blossom, Footprints, Premium Box.
5. **Bat Von Blood** הועבר ל-LoveClover (מיקום: תיק, לא מאומת).
6. **settings:**
   - CutesellsWoman: 91,924,117.
   - LoveBubbles: 6,349,914 (נוספה).
   - liquid = 990,443,580.
7. **LoveBubbles:** עודכנה ל-Merchant, Base 14 / Job 19.

**פתוח (לא ניתן לתקן בלי מידע מאושר):**
1. ✅ (נסגר 11:24) Abysmal Knight Card: אומת בצילום. שני הקלפים בחנות ZenyEmpire ב-3,300,000. ההערה הישנה על מכירה הייתה שגויה.
2. **יתרות שלא נבדקו היום:**
   - LoveClover: לא ידוע.
   - Cuteanddeadly: אושר אישר ב-11:25 שלא השתנה מאז 2/11.
   - buffsareus: אושר אישר ב-11:26 שלא השתנה.
   - ZenyEmpire: אומת היום (3/11 11:24), 492,420,690.
3. **רמות CutesellsWoman** לא רשומות.
4. **פריטים שלא נמצאו:**
   - Peerless Ancient Morocc Jewelry, Variant Shoes ×2, קלף Resentment.
   - Empathizer Card, Bloody Branch שני, High Adventurer Suit/Sandals.
   - כ-5 פריטים במחסן הגילדה ו-24 פריטי Armor במחסן הראשי לא זוהו.
   - כל אלה נשארו במסד ומסומנים, ולא נמחקו.
5. **מחירי שוק:** אין במסד אף מחיר שוק (אוסף market ריק). לכן "שווי שוק משוער" באתר מציג 0.
6. **רווח לא ידוע:** לכל 4 המכירות אין עלות קנייה, ולכן הרווח שלהן לא ידוע. האתר מציג אותן תחת "חסרה עלות".

**משימות תפעוליות:**
- **VIP של oshen11:** אי אפשר להפעיל את הקופסה החדשה כל עוד המנוי הנוכחי פעיל. הוא נגמר בערך ב-21:25 היום. תזכורת קבועה ל-21:20.
- **LoveClover:**
  - להגיע ל-Job 10 ולהחליף ל-Merchant (`/navi alberta 36/42`, אחר כך `/navi alberta_in 56/43`).
  - להמשיך ל-Job 19 כדי לפתוח חנות.
  - המטרה: שתחליף את החנות הרגילה של חשבון oshen11.
- **Crimson Bow +15:** לבדוק ב-iromarket היסטוריה של +14/+15 ואת מחיר Hunter Fly Card.
- **מעקב "רוצה לקנות":** Costume Fluttering Cherry Blossom כבר נקנה. נשארו RSX-0806, Ultra Limacina + Dim Glacier Follower [1], Bloody Branch.
- **לבדוק:**
  - שווי מטילים אצל High Value Trader.
  - מחיר Anger of Thanatos Card.
  - מחירים ל-Costume Crown (נכנס ל-LoveBubbles), Fishbone Hair ו-Spiritual Ring.
  - 317 פריטי קבוצה D שלא נבדקו בשוק.
- **מעקב אחר OnlineZenyMaster:** קנה את ה-Big Crossbow, ונראה שהוא סוחר. אם יציב אותו מחדש, המחיר שלו יראה את ערך השוק.
- **שמירת סטטיסטיקות מדיסקורד:** רק לפי בקשה. הבאה בערך ב-9/11.

## 10. קישורים לגרסאות העדכניות

- **אתר (חי):** https://claude.ai/artifact/TYcXBrk3GzaNTtcz2kKQBx (v21)
- **הדוח הזה ונספחיו:** קישורי raw ב-GitHub. הם מופיעים בהודעה ל-אושר ובקובץ `handover/README` במאגר.
- **ייצוא מלא של המסד (אחרי התיקונים):** `handover/db_export_2026-11-03.json`
- **גיבוי לפני התיקונים:** `/mnt/project-files/zeny-empire/backup-before-fixes-2026-11-03.json`
- **מלאי לפי שורה:** `handover/inventory_db_2026-11-03.csv`
- **קוד האתר:** `/mnt/project-files/zeny-empire/zeny-empire-v21.html`. יש גם עותק ב-backup-2026-11-02.
- **תמונת מצב קודמת ל-ChatGPT:** github.com/benfederman1-svg/zeny-empire-data, קובץ summary.txt מ-2/11 (מיושן).

---

**כללי העבודה החדשים שנקלטו:**
- Claude לא נותן הוראות מסחר ולא משנה מחירים על דעת עצמו.
- אין מחיקת היסטוריה, ואין איפוס של מחירים או כמויות בלי הוראה.
- פריט שנמכר לא חוזר למלאי.
- ציוד ה-Windhawk מוגן.
- מחיר מבוקש, הצעת קנייה ועסקה נשמרים בנפרד.
- כל שינוי בנתונים מתועד.
