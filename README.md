# Boostrap-website
Upotrebom bootstrap frameworka pravimo web stranicu po želji klijenta (recimo nekog jpg, png formata koji nam on pošalje)
Koristimo željene fontove, stilove koje ćemo otkucati u css fajlu pa taj fajl importovati u naš glavni html fajl
Formiramo konjtejnere kako nam odgovaraju (6-6 ili 4-4-4 ili 3-3-3-3 ...)
Ikonice preuzimamo sa font awesome (Fa-layer-group Fa-mobile-screen, fa-code
Fa-layer-group, fa-wrench, fa-table-layout, fa-book-blank, fa-code, fa-puzzle-piece-simple)
Dodajemo bootstrap klase za formatiranje tamo gde je to moguće
class=”text-center” poravnavamo sadržaj kontejnera centralno. Primenićemo to na kontejner slike telefona i kontejnere ikonica
class=”pull-right” ili class=”float-end” (zavisno od verzije bootstrapa) lepi taj kontejner uz desnu ivicu, tako da se radi text-wrapping okolo elementa. Primenićemo to na dve ikonice u predzadnjem kontejneru - smestićemo ikonice u div.
Dodajemo padding i margin tamo gde je potrebno da bismo dobili adekvatan prazan prostor. 
Postavićemo senke oko 3x2 sekcije sa ikonicama. Upotrebićemo box-shadow css svojstvo upotrebom nekog box-shadow generatora
Primenićemo col-xs- col-sm- col-md- i col-lg- tako da blokovi sadržaja dobiju odgovarajući prostor na ekranu, zavisno od klase ekrana.
Na mobilnom telefonu sve treba da ide jedno ispod drugog
Na tabletu siva sekcija, u kojoj je 6 blokova u dva reda, treba da se rasporedi u 3x2 (po dva bloka u tri reda)
Prilagodićemo navbar tako da se na sm i xs ekranima umesto linkova prikaže hamburger meni
Prilagodićemo navbar tako da se uvek vidi na vrhu ekrana ( “top fixed navbar”) 
Dodaćemo css kod u still.css koji će se primenjivati na media=print, prilikom štampanja stranice, tako da stranica bude print-friendly.
Prilagođava se za crno-belu štampu (tipičan laserski štampač)
Prilagodićemo boje ---> Pozadina svih sekcija treba da bude bela. Ostavićemo horizonalne ivice-linije između sekcija
Tekst treba da bude crne boje, ukloniće se footer sekciju, u navbar sekciji ostaće samo logo
Slika telefona treba da bude široka 4cm




