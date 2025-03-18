# Vizsgaremek - Borbély Attila, Hatta Bálint Dániel, Kárpáti Ramón

2025.02.12 - (Bálint)elkészítettem a szükséges HTML alapot, a kezdőoldallal.
2025.02.19 - (Bálint)hozzáadtam a weboldalhoz a kosárba helyezés funkciót, beállítottam az árakat, és hozzáadtam a fizetés funkciót, így már lehetne rendelni az oldalról. A termékek oldalon hozzáadtam egy funkciót, hogy azok 
             az ügyfelek, akik már rendeltek a megadott parfümből, tudjon róla véleményt írni. Ezen kívül hozzáadtam a regisztráció és a bejelentkezés felületet is, ennek segítségével lehet megnézni a véleményeket egy parfümről, illetve így lehet róla véleményt írni. A fiók beállításokban a felhasználó megtudja tekinteni az eddigi leadott rendeléseit. 

Az admin panel kapott egy új funkciót, amivel lehet törölni a regisztrált felhasználókat.

Hozzáadtam a termékek oldalra a szűrési lehetőséget, így lehet szűrni férfi-női-unisex termékek közül, és a megjelenés sorrendjét is ár alapján belehet állítani

2025.03.04 - (Bálint) A html fájlokat átalakítottam php fájlokra, de maga a HTML kód megmaradt. Hozzácsatoltam az adatbázist. 
2025.03.18 - (Bálint) Feltöltöttem a végleges weboldalt. Hozzáadtam a remove from cart php kódot, az add_product kódot, az add_to_cart kódot, a checkoutot, a checkout_processt. A config.php konfigurációját átállítottam, hogy az új, a tárhely szolgáltató adatbázisához csatlakozzon. Hozzáadtam a login_proccest, a logoutot, a register_proccest, a termekek.php oldalt frissítettem, és online, az add_product kód segítségével hozzáadtam a parfümöket. Továbbá megírtam az update_kosar php függvényt. Ezek mind külön fájlban vannak, hogy könnyen átlátható legyen a szerkezete a weboldalnak. 
