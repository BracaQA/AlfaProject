# Završni projekat IT Bootcamp
Testiran je sajt https://phptravels.com/demo/

Struktura projekta je sledeća:
- pages - pom klase
- tests – testovi
- utils - pomoćne klase

Korišćen je Selenium WebDriver, Apache POI i ChromeDriver.

### TravelsLogin
POM pribavlja elemente označene na slici. Napisan je test (**TravelsLogInTest**) koji ispituje login korisnika. 
![](https://i.imgur.com/a6m77VK.png)

### TravelsMenu
Testiran je levi meni sajta -  TravelsMenu.  POM pribavlja objekte označene na slici. Test **TravelsMenuCheckTest** testira da li meni radi, tj. da li je moguće posetiti sve stranice koje su pribavljene.

![](https://i.imgur.com/L5q0mUP.png)

![](https://i.imgur.com/tjkBLzE.png)

![](https://i.imgur.com/XkKF9Ea.png)

### TravelsCars
Na stanici za Rent-a-Car napisan je POM i odgovarajući test (**CarsCountTest**) koji ispituje:
- Da li je broj modela koji rentiramo jednak 10 - *Name*
- Da li je ukupan broj narudžbina veći od 50 – *Orders* 

![](https://i.imgur.com/4XxATT3.png)

### TravelsCarsExtras
Na stranici Cars-Extras omogućeno je dodavanje ekstra stvari za auto. Popunjena su sva polja na slici i napisan je test (**TravelCarsExtrasAddTest**) da li je uneta stvar dodata u tabeli. 

![](https://i.imgur.com/dczW5qC.png)

![](https://i.imgur.com/wulvckW.png)

### TravelCustomer
Na stranici Accounts - Customers je omoguceno dodavanje naloga korisnika.

Informacije se unose u polja koja su oznacena crvenom bojom.

Zatim je testirano (**TravelsCustomerEditTest**) da li je korisnik uspesno dodat uz pomoć Search opcije ispod tabele.

![](https://i.imgur.com/EzQBMod.png)

![](https://i.imgur.com/Hd25yOT.png)

### TravelsLogInUsingApachePoi
Testirano je da li je moguće izvršiti login korisnika koristeći direktno podatke iz excel tabele.

![](https://i.imgur.com/vJsfgnw.png)
