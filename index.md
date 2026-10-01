# Politika privatnosti — Šume

Posljednje ažuriranje: 1. listopada 2026.

Ova politika objašnjava obradu podataka pri korištenju mobilne aplikacije Šume za Android i iOS, identifikatora `hr.playbyte.sume`.

Izdavatelj aplikacije: [IME ILI NAZIV IZDAVATELJA], pod brendom Playbyte.

Kontakt za privatnost i podršku: [KONTAKTNI EMAIL].

## 1. Podaci spremljeni na uređaju

Šume ne zahtijeva izradu korisničkog računa.

Aplikacija na vašem uređaju sprema odabrane katastarske čestice, njihove službene podatke i geometriju, korisničke nazive, ikonice, grupe čestica, pristupne točke i datume spremanja.

Ti se zapisi ne sinkroniziraju na poslužitelj izdavatelja. Izdavatelj nema udaljeni pristup vašoj lokalnoj bazi.

Korisnički nazivi, ikonice i članstvo u grupama ne šalju se servisima za pretraživanje ili izračun rute. Koordinate odredišta mogu se poslati servisu za rute kada koristite navigaciju.

## 2. Lokacija

Uz vaše dopuštenje aplikacija koristi položaj uređaja za prikaz trenutačne lokacije, odabir područja na karti, navigaciju i vizualni prikaz granica.

Za navigaciju mogu se obrađivati i podaci o preciznosti položaja, brzini i smjeru kretanja. Šume ne sprema trajnu povijest vašeg kretanja.

Pri izračunu ili ponovnom izračunu rute vanjskom servisu šalju se koordinate polazišta i odredišta te način kretanja, primjerice automobil ili hodanje. Polazište može biti vaša trenutačna lokacija.

Praćenje lokacije u aplikaciji pauzira se kada aplikacija prijeđe u pozadinu. Trenutačna verzija ne pruža navigaciju pri zaključanom zaslonu.

Dopuštenje za lokaciju možete odbiti ili opozvati u postavkama uređaja. Funkcije koje ovise o lokaciji tada mogu biti nedostupne.

## 3. Kamera, senzori i vizualni prikaz granica

Kamera i senzori uređaja koriste se za funkciju vizualnog prikaza granica i smjera kroz proširenu stvarnost, odnosno AR.

Kod aplikacije ne sprema fotografije ili videozapise i ne šalje snimke kamere izdavatelju. Obrada prikaza i položaja virtualnih oznaka odvija se na uređaju.

Na iOS-u koristi se Apple ARKit. Na Androidu koristi se Google Play Services for AR, odnosno ARCore.

Google Play Services for AR pruža Google, a njegova obrada podataka uređena je Googleovom politikom privatnosti. ARCore može obrađivati identifikatore korisnika ili uređaja, podatke o korištenju API-ja te podatke o izvedbi i dijagnostici radi rada i poboljšanja AR funkcija.

Šume ne koristi ARCore Cloud Anchors ni Google Geospatial API.

Više informacija:

- [Googleova politika privatnosti](https://policies.google.com/privacy)
- [Kako Google Play Services for AR obrađuje podatke](https://support.google.com/ar/answer/12148145)
- [Appleova politika privatnosti](https://www.apple.com/legal/privacy/)

Kameru možete onemogućiti u postavkama uređaja. Funkcije karte i spremljenih čestica ostaju dostupne bez AR prikaza.

## 4. Vanjski servisi

Za pojedine funkcije aplikacija šalje mrežne zahtjeve sljedećim servisima.

### Katastar — DGU i Uređena zemlja

Pri pretraživanju i osvježavanju šalju se naziv ili šifra katastarske općine, broj čestice ili koordinate područja odabranog na karti.

Pri prikazu katastarskih granica servis prima zahtjeve za prikazano područje karte.

Službeni podaci dohvaćaju se preko servisa na domeni `api.uredjenazemlja.hr`.

### Kartografska podloga — OpenFreeMap

Za prikaz podloge koriste se servisi na domeni `tiles.openfreemap.org`. Zahtjevi za kartografske podatke otkrivaju područje karte koje se učitava.

### Pretraga mjesta — Photon

Tekst koji upišete u pretragu gradova i mjesta šalje se Photon servisu na domeni `photon.komoot.io`.

### Rute i prijedlog prilaza — Valhalla

Za izračun rute šalju se koordinate polazišta i odredišta te profil kretanja. Za prijedlog prilaza mogu se poslati uzorkovane koordinate uz granice čestice.

Trenutačno se koristi servis na domeni `valhalla1.openstreetmap.de`.

### Otvaranje službenog portala

Ako odaberete provjeru vlasništva na Uređenoj zemlji, otvara se vanjski portal `oss.uredjenazemlja.hr`. Njegova obrada podataka uređena je pravilima tog portala.

### Tehnički podaci zahtjeva

Operateri vanjskih servisa mogu primiti IP adresu, vrijeme zahtjeva, identifikaciju aplikacije i sadržaj zahtjeva te ih obrađivati radi pružanja, zaštite i održavanja svojih usluga.

Izdavatelj Šuma ne upravlja njihovim zapisima ni rokovima čuvanja. Ovisno o operateru, obrada se može odvijati izvan vaše države, uključujući izvan Europskog gospodarskog prostora.

## 5. Oglasi i analitika

Trenutačna verzija Šuma ne prikazuje oglase i nema vlastiti sustav marketinškog praćenja, analitike ponašanja ili slanja izvještaja o rušenju aplikacije.

To ne isključuje obradu tehničkih i dijagnostičkih podataka koju provode operacijski sustav, trgovine aplikacija i vanjski servisi opisani u ovoj politici.

## 6. Čuvanje i brisanje

Spremljene čestice i grupe ostaju u lokalnoj bazi dok ih ne izbrišete ili uklonite podatke aplikacije.

Pojedinu česticu možete izbrisati kroz njezine detalje. Razdvajanje grupe zadržava njezine čestice kao pojedinačne zapise.

Na Androidu sve lokalne podatke možete ukloniti kroz postavke aplikacije odabirom brisanja podataka. Na iOS-u možete izbrisati aplikaciju; opcija rasterećivanja aplikacije može zadržati njezine podatke.

Ako postoje sigurnosne kopije uređaja, njihovim čuvanjem i brisanjem upravljate kroz odgovarajuće postavke uređaja ili usluge za sigurnosne kopije.

Izdavatelj ne može udaljeno izbrisati lokalnu bazu na vašem uređaju.

Ako nam pošaljete poruku za podršku, obrađujemo adresu e-pošte i podatke koje navedete radi odgovora. Čuvamo ih koliko je potrebno za rješavanje upita i ispunjenje primjenjivih obveza.

## 7. Sigurnost

Mrežni servisi navedeni u ovoj politici koriste HTTPS. Lokalni podaci nalaze se u prostoru aplikacije kojim upravlja operacijski sustav.

Za zaštitu uređaja preporučujemo zaključavanje zaslona i redovita sigurnosna ažuriranja. Nijedan način pohrane ili prijenosa ne može jamčiti potpunu sigurnost.

## 8. Vaše mogućnosti i prava

Možete upravljati dopuštenjima za lokaciju i kameru, uređivati i brisati lokalne zapise te koristiti dostupne funkcije bez davanja nepotrebnih dopuštenja.

Za osobne podatke koje obrađuje izdavatelj možete, prema primjenjivim propisima, zatražiti pristup, ispravak, brisanje, ograničenje obrade ili ostvarivanje drugih prava.

Zahtjev pošaljite na: [KONTAKTNI EMAIL].

Za podatke koje samostalno obrađuju vanjski operateri možete se obratiti tim operaterima. Ako smatrate da su vaša prava povrijeđena, možete podnijeti pritužbu nadležnom tijelu za zaštitu podataka; u Hrvatskoj je to Agencija za zaštitu osobnih podataka (AZOP).

## 9. Posjet ovoj stranici

Ova politika objavljena je putem GitHub Pagesa. GitHub može obrađivati tehničke podatke posjeta, uključujući IP adresu i podatke o zahtjevu, prema vlastitoj politici privatnosti.

[GitHubova politika privatnosti](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)

## 10. Promjene politike

Politiku ćemo ažurirati kada se promijeni obrada podataka ili funkcionalnost aplikacije. Datum posljednjeg ažuriranja naveden je na vrhu stranice.

Prije uvođenja kupnji, korisničkih računa, sinkronizacije ili dodatnih servisa ovu ćemo politiku uskladiti s njihovom stvarnom obradom podataka.
