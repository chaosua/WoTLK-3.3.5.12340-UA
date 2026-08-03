# WoW-WoTLK-3.3.5.12340-UA-localization
Українська локалізація клієнтської частини
Патч заміни для ruRU версії, частково enUS/enGB

Бажаючі можуть долучитися до перекладу пуллреквестами:
- кодування текстових файлів UTF8
- текстові колонки починаються і закінчуються подвійними лапками
- редагувати шось окрім тексту - не можна
- якщо в тексті є технічні змінні (це особливо зустрічається в поштових текстах і в описі заклинань вони починаються з символа $ ) - їх чіпати не можна, можна лише пересунути в інше місце якщо порушується зміст перекладеного.
приклад таких змінних: $s1, $s2, $d, $/5;s1, $g, $N
- в деяких файлах є колонки з повторюваним текстом, редагувати бажано обидві синхронно,
якщо не виходить то пріорітетніша друга колонка з текстом (ruRU клієнт) над першою (enGB/US клієнт)
- про помилки перекладу можна писати в розділі Issues
https://github.com/chaosua/WoTLK-3.3.5.12340-UA/issues

Мій поточний спосіб Notepad++
- відкрити всі файли одночасно в ньому і робити масову заміну слів, словосполучень
- корекція дрібних нестиковок і плавності читання

Чому саме для ruRU?
- заміщення російської
- швидкість перекладу
- аддони, які зав'язані на назвах з конкретної локалізації (назви регіонів, заклинань, скілів тощо) треба буде адаптовувати лише під одну мову клієнта

Відносно завершений переклад:
Achievement_Category.dbc.csv - en/ru
-Achievement_Criteria.dbc.csv - en/ru
-AreaPOI.dbc.csv - en/ru
AuctionHouse.dbc.csv - en/ru 
BarberShopStyle.dbc.csv
BattlemasterList.dbc.csv - en/ru
Cfg_Categories.dbc.csv - en/ru
CharTitles.dbc.csv - en/ru
ChatChannels.dbc.csv - en/ru
ChrClasses.dbc.csv - en/ru
ChrRaces.dbc.csv - en/ru
CreatureFamily.dbc.csv - en/ru
CreatureType.dbc.csv - en/ru
Exhaustion.dbc.csv - en/ru 
GameTips.dbc.csv - en/ru 
ItemClass.dbc.csv - en/ru
ItemSubClass.dbc.csv - en/ru
ServerMessages.dbc.csv - en/ru
SkillLine.dbc.csv - en/ru
SpellMechanic.dbc.csv- en/ru
SpellShapeshiftForm.dbc - en/ru
TalentTab.dbc.csv - en/ru
WowError_Strings.dbc.csv - en/ru
