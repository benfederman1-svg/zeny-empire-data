# ZE-010: אילו ביצי חיות נמכרות הרבה, ואם כדאי לייצר אותן (iRO Chaos)
8/11/2026, 08:30 שעון ישראל. מחקר בלבד: לא קניתי, לא מכרתי ולא שיניתי שום דבר במאגר או באתר. המשך ל-ZE-009 (Baphomet).

**סימונים:** ✅ מאומת בשוק החי או במקור iRO · ⚠ מקור עקיף (rAthena / Divine Pride / kRO) · ❓ לא נמצא · 🔎 לבדוק במשחק

**מקורות:**
- **iRO Market (Chaos):** סריקה מלאה של כל מזהי הביצים 9001–9250 (דף מכירה + דף קנייה), 8/11 06:18 UTC (08:18 ישראל). 363 שורות. קובץ גולמי במחשב בבית: `Desktop\ZenyEmpire\market\scan_pet_eggs_2026-11-08.csv`. **סריקה חלקית** (תקרת 10 שורות): דפי 9121 Orc Hero, 9117 Corrupted Wanderer, 9062, 9140, וחיפושי Egg/Orc. ההיסטוריה באתר = ירידות מלאי, **לא מכירות מאומתות**, וזמינה רק ~10 ימים אחורה.
- **[DP]** Divine Pride (תצוגת iRO): item 9111, 9121, 9087, 9017, 25377, 25508, 25430.
- **[rA]** rAthena pet_db.yml (מבוסס kRO, לא iRO). **[HF]** hazyforest.com (ויקי kRO לא רשמי).

---

## 1. תקציר
| ביצה | אפשר לייצר? | עלות ייצור | מחיר שוק (מבוקש / היסטוריה) | מסקנה |
|---|---|---|---|---|
| **Orc Hero Egg (9121)** | כן, מ-High Orc Loyal | **~127.5M** + 10 Heroic Emblem (אין בשוק) | Neutral נמכר 40–45.5M; ללא תג 50–80M; Loyal מבוקש 72–122M | **NO-GO** – הפסד 50–85M לביצה |
| **Phreeoni Egg (9111)** | ❓ לא נמצא מתכון או מקור | – | 3 מוכרים 26–29M; היסטוריה 18.9–35M | **NO-GO** – אין דרך ייצור ידועה |
| **"Destroyer"** | – | – | **אין ביצה כזו ב-iRO Market** (בשם הזה יש רק Destroyer Boots) | 🔎 צריך את השם המדויק שראית |
| **"Loyal upgrade"** (Aliot, Chaotic Bapho Jr., Corrupted Wanderer, Rigid Nightmare Terror) | כן – רק האכלה (~יום) | 4M–29M | ביצה רגילה זולה, Loyal מבוקש פי 2 עד פי 60 | **TEST FIRST** – ניסוי אחד עד 5M |

- **אין אף הזמנת קנייה לאף ביצה בכל השוק.** כל הביקוש מבוסס רק על ירידות מלאי.
- הביצים שהכי "נמכרות" (לפי האתר) הן ביצים רגילות וזולות שמשמשות בסיס לפיתוח – לא ביצי MVP.

---

## 2. דירוג ביצים לפי יחידות שירדו מהמלאי (iRO Market)
"נמכרו" ו"ממוצע" = נתון האתר, מוסק מירידות מלאי (לא מאומת).

| # | ביצה (ID) | נמכרו | ממוצע | זול (בלי תג) | זול Loyal | מוכרים |
|---|---|---|---|---|---|---|
| 1 | Aliot Egg (9118) | 55 | 43.0M | **5.0M** | 80.0M | 7 |
| 2 | Chaotic Baphomet Jr. Egg (9130) | 51 | 32.0M | **3.97M** | 249M | 7 |
| 3 | Dokebi Egg (9019) | 46 | 5.66M | 5.0M | – | 2 |
| 4 | Poison Spore Egg (9013) | 41 | 5.0M | 5.0M | – | 1 |
| 5 | Corrupted Wanderer Egg (9117) ⚠חלקי | 41 | 103.4M | 25M (Neutral) / 28M | 150M | 10+ |
| 6 | Child Admin Beta Egg (9123) | 38 | 25.9M | 9.88M | 550M | 4 |
| 7 | Rigid Nightmare Terror Egg (9116) | 37 | 46.2M | 28.8M | 50M | 7 |
| 8 | Marionette Egg (9043) | 35 | 100.2M | 10.0M | 99M | 5 |
| 9 | Baby Desert Wolf Egg (9010) | 34 | 4.52M | 2.0M | – | 5 |
| 10 | Succubus Egg (9055) | 28 | 67.1M | 190M | – | 1 |
| – | High Orc Egg (9087) | 17 | 141.4M | – | 100M | 4 |
| – | Time Holder Egg (9171) | 15 | 815M | 400M | – | 8 |
| – | Cat o' Nine Tails (9096) | 14 | 341.5M | 300M | – | 2 |
| – | Wild Rose (9141) | 12 | 300M | – | 300M | 3 |
| – | Moonlight (9112) | 9 | 409M | 350M | 600M | 3 |
| – | Gloom Under Night (9122) | 5 | 644M | 629M | – | 2 |
| – | Baphomet (9137) | 3 | 599M | 499M (Neutral) | 699M | 3 |
| – | **Orc Hero (9121)** ⚠חלקי | 2 | 47.8M | 50.0M | 72M | 9+ |
| – | **Phreeoni (9111)** | 1 | 35.0M | 26.0M | – | 3 |

**לא נמצאו בשוק בכלל** (0 מוכרים/קונים/היסטוריה): Orc Warrior Egg (9017), Orc Lord Egg (9073), Orc Hero ישנה (9072), Kiel (9126), Desert Wolf (9129), Eddga (9136), Dark Lord, Dark Illusion, Wicked Nymph.

**למה ראית "הרבה" Orc Hero:** יש 9+ מודעות (6 Loyal, 3 בלי תג) – הרבה מוכרים, אבל רק 2 ירידות מלאי ב-10 ימים. היצע גבוה, ביקוש נמוך.

---

## 3. Orc Hero Egg (9121) – תהליך ועלות
**מסלול** (✅ DP + ⚠ HF): Orc Warrior → High Orc → Orc Hero. פיתוח רק ב-Loyal.

**שלב א: Orc Warrior Egg (9017)** – אילוף עם Orc Trophy (635) על Orc Warrior. ⚠ סיכוי 5% לפי rA. Orc Trophy ו-Orc Warrior Egg: **אין בשוק**.

**שלב ב: High Orc Egg (9087)** – מתכון ⚠ DP (שונה מ-kRO):
| חומר | כמות | שוק היום |
|---|---|---|
| Orc Trophy (635) | 3 | אין בשוק |
| Orcish Voucher (931) | 500 | רק הזמנת קנייה ב-150 (כלומר זול, פארם) |
| Orcish Sword (1124) | 1 | 300K |
| Cigarette (2267) | 1 | אין מוכרים; היסטוריה 10M (1/11) |
| Orc Helm (2299) | 1 | אין בשוק |
| Orc Warrior Card (4066) | 1 | 1.11M |
| Item 25430 (Mithril) | 2 | ⚠ DP לא מסמן אותו כקיים ב-iRO |
| Orc Warlord Token (25508) | 50 | אין בשוק; דרופ 48.5% מ-Orc Hero MVP |
→ **לא בר-ביצוע מהשוק.** חלק מהחומרים לא קיימים למכירה.

**שלב ג: Orc Hero Egg** – מתכון ✅ DP (זהה ב-kRO):
| חומר | כמות | מחיר | עלות |
|---|---|---|---|
| High Orc Egg [Loyal] | 1 | 100,000,000 (מבוקש הכי זול) | 100,000,000 |
| Heroic Emblem (968) | 10 | ❓ אין בשוק | ❓ |
| Orc Warrior Card (4066) | 10 | 1,110,000 (296 יח') | 11,100,000 |
| Orc Baby Card (4375) | 10 | 889,000 | 8,890,000 |
| Essence of Powerful Soul (25375) | 30 | 250,000 (346 יח') | 7,500,000 |
| **סה"כ (בלי Emblems)** | | | **127,490,000** |

**רווח אחרי מס 5%:**
| מחיר מכירה | נטו | רווח |
|---|---|---|
| 45.5M (Neutral, היסטוריה) | 43.2M | **-84.3M** |
| 72M (Loyal הכי זול, מבוקש) | 68.4M | **-59.1M** |
| 79.9M (המחיר שלנו היום) | 75.9M | **-51.6M** |

- **מסקנה: NO-GO.** ביצת High Orc Loyal (בסיס) נמכרת ביותר מ-Orc Hero (תוצאה). לקנות Orc Hero מוכנה ב-50M זול יותר מלייצר.
- הבונוס של Orc Hero ב-Loyal (✅ DP): ATK +7%, נזק קריטי +3%. אוכל: Luxurious Pet Food (25377) – NPC Pet Groomer payon 177/131 ב-10,000 (⚠ DP, לא אומת ב-iRO). אין בשוק.
- **הרשומה שלנו:** ZenyEmpire מוכרת Orc Hero Egg [Loyal] ב-79,900,000 – מקום 2 מתוך 6 מודעות Loyal. Mr Chen מבקש 72,000,000. המודעה הכי זולה (בלי תג) 49,999,999. לא נרשמה אף מכירה מתוארכת של Loyal.

---

## 4. Phreeoni Egg (9111)
- **איך משיגים:** ❓ **לא נמצא.** DP: "No sources recorded". אין חיה שמתפתחת ל-Phreeoni באף מקור. HF (kRO) מציג רק 30 Essence + Luxurious Pet Food בלי חיית בסיס. כנראה ביצה מאירוע/קופסה.
- **שוק:** 3 מוכרים, 26.0M–29.0M (בלי תג). היסטוריה: 14/10 29–30M (3 יח'), 28/10 18.9M (2), 30/10 19.5M (3), 4/11 35M (1). כ-9 יחידות ב-3 שבועות.
- **בונוס Loyal** (✅ DP): HIT +18, Perfect Hit 15%.
- **מסקנה: NO-GO לייצור** – אין מתכון. הקנייה-מכירה (flip) בטווח 19–35M צרה מדי אחרי מס.

---

## 5. ממצא מרכזי: "Loyal upgrade" – לקנות ביצה זולה, להאכיל, למכור Loyal
אותה תופעה שראינו ב-ZE-009 (Chaotic Baphomet Jr.) חוזרת בעוד ביצים. אלה חיות מפותחות שאוכלות Pet Food רגיל ותומכות ב-Auto Feed (⚠ rA), כך שהגעה ל-Loyal לוקחת **בערך 15–21 שעות** (חישוב ZE-009).

| ביצה | קנייה (זול) | ממוצע אתר | Loyal מבוקש זול | רווח – בסיס (ממוצע) | רווח – אופטימי (Loyal) | Auto Feed |
|---|---|---|---|---|---|---|
| Aliot (9118) | 5.0M | 43.0M | 80.0M | **35.7M** | 70.9M | ⚠ כן, Pet Food |
| Chaotic Baphomet Jr. (9130) | 3.97M | 32.0M | 249M | **26.4M** | 232.5M | ⚠ כן, Pet Food |
| Corrupted Wanderer (9117) | 28.0M | 103.4M | 150M (1 מודעה) | **70.1M** | 114.4M | ⚠ כן, Pet Food |
| Rigid Nightmare Terror (9116) | 28.8M | 46.2M | 50.0M | **15.1M** | 18.6M | ⚠ כן, Pet Food |
| Marionette (9043) | 10.0M | 100.2M | 99M | – | – | ❌ אוכל מיוחד, אין Auto Feed לפי rA |

(רווח = מכירה × 0.95 פחות קנייה פחות ~100K אוכל.)

**תרחיש שמרני לכולן: ~0 עד הפסד קטן.** אם אין קונה ל-Loyal, מוכרים בחזרה במחיר רגיל ומפסידים רק זמן ואוכל.

**⚠ למה זה עדיין לא מוכח:**
- כל נקודות ההיסטוריה המתוארכות הן במחיר **הזול** (Aliot 4.9–6.0M × 4; Chaotic 5M; Marionette 14M). **אין אף מכירה מתוארכת של ביצה Loyal.**
- מצד שני, הממוצע של האתר (Aliot 43M על 55 יח') גבוה בהרבה מכל הנקודות הזולות. זה רמז שחלק מהעסקאות היו במחיר גבוה – אבל לא ידוע אם אלה Loyal.
- 0 הזמנות קנייה. המחירים ל-Loyal הם מחירים מבוקשים בלבד.

---

## 6. המלצה
- **Orc Hero: NO-GO** לייצור. עלות 127.5M+ מול מכירה 45–80M.
- **Phreeoni: NO-GO.** אין מקור ידוע.
- **Destroyer:** 🔎 לא קיימת ביצה בשם הזה. אם תצלם את המודעה שראית, אבדוק.
- **Loyal upgrade: TEST FIRST – ניסוי אחד בלבד, עד 5M** (לפי מדיניות הניסויים):
  1. לקנות **Aliot Egg** אחת ב-~5.0M (הכי זול, הכי הרבה תנועה: 55 יח'). 
  2. לבקוע, Auto Feed + Pet Food בתיק, חנות פתוחה עם החיה בחוץ (כמו בנוהל ZE-009).
  3. 🔎 לרשום אינטימיות בהתחלה ואחרי שעתיים – זה גם מאמת את קצב ההאכלה לפיילוט ה-Baphomet.
  4. ב-Loyal: להציע ב-~45M (מתחת למודעת ה-Loyal הזולה, 80M, וליד ממוצע האתר).
  5. **תנאי הרחבה:** מכירה בפועל תוך 7–10 ימים. רק אז לשקול Corrupted Wanderer (הון 28M) או Chaotic Baphomet Jr.
- ההחלטה – של אושר ו-ChatGPT.

*מוכן על ידי Claude מנתוני שוק וקוד פתוח. אלה נתונים, לא הוראות מסחר.*


---

## 7. עדכון 08:45 – מקורות השגה חדשים (✅ האתר הרשמי של iRO + iRO Wiki)
- **אירוע Easter Egg Hunt 2026** (renewal.playragnarok.com/news/eventdetail.aspx?id=2021, עמוד מ-6/4/2026): ה-NPC Baron Pan Doo מחליף ביצים תמורת מטבעות האירוע:
  - **Orc Hero Egg:** 300 [Event] 2026 Easter Egg + 10 Easter Collectible Coin.
  - **Corrupted Wanderer, Rigid Nightmare Terror**, Blue Moon Loli Ruri, Fire Golem: כל אחת 60 Easter Egg + 2 Coin.
  - כנראה מכאן ההיצע הגדול של Orc Hero בשוק. ❓ אין בעמוד תאריך סיום – לא ידוע אם האירוע עדיין פעיל.
  - **המשמעות:** חישוב ההפסד בסעיף 3 נכון רק למסלול האבולוציה. מי שמשיג Orc Hero מהאירוע משלם רק בזמן.
- **Phreeoni Egg** (iRO Wiki): לא מאלפים ולא אבולוציה. מגיעה **ממכונת אירועים** תמורת **30 Essence of Powerful Soul (25375)**.
  - עלות: 30 × 250K = **7.5M** (346 יח' ב-250K היום). מכירה ב-26M → נטו 24.7M → **רווח ~17M לביצה**.
  - ❓ לא ידוע אם המכונה פעילה היום, ואיפה היא. 🔎 לבדוק במשחק לפני כל קנייה.
- **"Destroyer":** ייתכן שהכוונה ל-Ground Deleter (9035) או Earth Deleter (9098). ל-Earth Deleter יש מודעה אחת ב-214.7M ו-2 יחידות ירדו מהמלאי. 🔎 צריך את השם המדויק מהחנות.
- **מתכוני אבולוציה נוספים** (⚠ dpRO / iRO Wiki, החומרים לא תומחרו):
  - Aliot ← Teddy Bear Loyal: 10 Opal, 100 Honey, 500 Rusty Screw, 1 Teddy Bear Card.
  - Chaotic Baphomet Jr. ← Baphomet Jr. Loyal: 100 Yellow Herb, 300 Evil Horn, 300 Brigan, 1 Chaotic Baphomet Junior Card.
  - Corrupted Wanderer ← Wanderer Loyal: 50 Hand of God, 100 Fabric, 1 Wanderer Card, 500 Skull.
  - Rigid Nightmare Terror ← Nightmare Terror Loyal: 100 Blue Herb, 100 Shell, 1 Nightmare Terror Card, 500 Burning Horseshoe, 2 Mithril.
- **המלצה מעודכנת:** Orc Hero לייצור באבולוציה – NO-GO (ללא שינוי). **Phreeoni – TEST FIRST** אם מכונת האירוע קיימת. Loyal upgrade (Aliot) – TEST FIRST (ללא שינוי).
