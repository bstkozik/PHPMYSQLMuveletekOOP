MYSQL műveletek (Select,Insert,Delete,Update) végrehajtása PHP nyelven. Objektum orientáltan megírva.

HASZNÁLAT:
1. lépés: Importáljuk a pelda_adatbazis.sql fájl a MySQL kliensünkbe!
2. lépés: Az index.php fájlt tegyük a megfelelő helyre, majd nyissuk meg a böngészőnkben és a szövegszerkesztőnkben is!

A kód 2 PHP blokkra van felbontva:

-Az első blokkban található az osztálydefiníció (Adattagok+függvények). Ezt lehet alapként használni más projektekbe. 
(Természetesen át kell majd írni a megfelelő sorokat: adatbázis neve,táblanevek,oszlopnevek stb..)
  
-A második blokkban történik a függvények tesztelése. Egyesével ki lehet próbálni minden műveletet a kommentek értelmezése után.
(Ezt csupán fejlesztői tesztelésre/ellenőrzésre alkalmas. Valós projekben használjunk formokat, amelyeket a kliensoldalon
töltünk ki, majd a szerver oldalon validálunk. A megfelelő bemeneti adatokkal hívjük meg az 1. blokkban lévő függvényeket)
