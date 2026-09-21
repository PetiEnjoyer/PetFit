#PETFIT

##Projekt leírás

A PetFit egy inteligens kisállat-webshop, amely nemcsak termékeket kínál, hanem személyre szabott ajánlásokat is ad a felhasználó kisállatának leírásának alapján

A rendszer ezek alapján képes lesz olyan termékeket ajánlani, amelyek jobban megfelelnek az adott kisállat igényeinek.

A projekt célja egy teljes értékű webáruház létrehozása frontend, backend és adatbázis használatával.

---


##Fő funkciók

-Felhasználói regisztráció
-Bejelentkezés
-Felhasználói profil
-Kisállat profil létrheozása
-Kisállat profil módosítása
-Kisállat profil törlése
-Termékek megjelenítése
-Termékkategóriák
-Termékek keresése
-Termékek szűrése
-Kosár
-Kedvencek
-Rendelés leadása
-Rendelési előzmények
-Termékértékelések
-Admin felület
-Termékek hozzáadása
-Termékek módosítása
-Termékek törlése
-Készletkezelés

---

##Egyedi funkciók

###Smart Match

A Smart Match rendszer a kisállat profilja alapján összehasonlítja az állat adatait a termék ajánlott tulajdonságaival. 

A rendszer például figyelembe veheti:

-állat fajtája
-testméret
-testsúly
-életkor
-aktivitási szint

Ez alapján a rendszer egy kompatibilitási értéket adhat a termékehz.

Példa:
-faj egyezés: 30 pont
-súly egyezés:20 pont
-kor egyezés:15 pont
-méret egyezés:20 pont
-aktivitási szint egyezés:15 pont

Maximális pontszám: 100

---

###Smart Size Finder

 Bizonyos termékeknél, például hámoknál vagy nyakörveknél a rendszer segít kiválasztani a megfelelő méretet.

 A felhasználó megadhatja például:
 -nyakkörfogat
 -mellkaskörfogat
 -testsúly

 A rendszer ezek alapján ajánl egy megfelelő méretet.

 ---

 ##Használt technológiák 

 ###Frontend

 -HTML
 -CSS
 -JavaScript

 ###Backend 

 -Node.js
 Express.js

 ###Adatbázis

 -MySQL

 ---

 ##Tervezett adatbázis táblák

 -users
 -pets
 -products
 -categories
 -product_sizes
 -cart_items
 -favorites
 -orders
 -order_items
 -reviews
 -product_pet_rules

---

##Adatbázis kapcsolatok

Egy felhasználóhoz több kisállat tartozhat.
Egy felhasználó több rendelést adhat le.
Egy kategóriához több termék tartozhat.
Egy rendelés több terméket tartalmazhat.
 Egy termékhez több méret és több értékelés tartozhat.

 ---

 ##Tervezett oldalak

 -Főoldal
 -Terméklista
 -Termékoldal
 -Kategóriaoldalak
 -Regisztráció
 -Bejelentkezés
 -Felhasználói profil
 -Kisállat profil
 -Kosár
 -Kedvencek
 -Rendelés
 -Admin felület

 ---

 ##A projekt célja

 A projekt célja egy olyan modern webáruház elkészítése, amely több funkciót kínál egy hagyományos webshopnál.

 A PetFit fő különlegessége a személyre szabhatóság a kisállat-profilok között és az ezekre épülő termékajánló rendszer.

 A projekt során szeretnénk gyakorolni és bemutatni: 
 -frontend fejlesztést
 -backend fejlesztést
 -REST API használatát
 -adatbázis-kezelést
 -CRUD műveleteket
 -felhasználói autentikációt
 -kliens és szerver közötti kommunikációt

 ---

 ##Fejlesztési terv

 1. Weboldal alapstruktúrájának elkészítése(Az oldal gerince)
 2. Felhasználói felület megtervezése
 3. Adatbázis megtervezése
 4. Node.js backend létrehozása
 5. MySQL adatbázis összekapcsolása a backenddel
 6. Termékkezelés elkészítése
 7. Regisztráció és bejelentkezés
 8. Kisállat profil rendszer
 9. Kosár és rendelési rendszer
 10. Smart Match rendszer
 11. Smart Size rendszer
 12. Admin felület
 13. Tesztelés
 14. Hibajavítás
 15. Dokumentáció elkészítése


  
