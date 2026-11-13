# Atmos Ishrana

**Atmos Ishrana** je aplikacija za praćenje kalorija i nutrijenata: dnevnik ishrane po obrocima, tablica namirnica, pretraga proizvoda na internetu i **skeniranje barkoda (EAN) sa ambalaže**. Radi na telefonu, tabletu i računaru, a podatke po želji čuva na **tvom Google Drive-u**.

**Otvori aplikaciju:** https://gembirdt-bit.github.io/atmos-ishrana/

## Mogućnosti

- **Dnevnik** — doručak, ručak, večera i užine; preostale kalorije, proteini, ugljeni hidrati, masti, vlakna, šećeri i so; „Kao juče“ za ponavljanje obroka
- **Skeniranje barkoda** 📷 — kamera prepoznaje EAN-13 / EAN-8 / UPC kod, a podaci o proizvodu (kalorije i nutrijenti na 100 g, porcija, Nutri-Score) stižu iz otvorene baze [Open Food Facts](https://world.openfoodfacts.org). Ako proizvod nije u bazi, prepišeš vrednosti sa ambalaže i aplikacija ga sledeći put prepoznaje odmah. Može i ručni unos broja ili slika barkoda.
- **Pretraga proizvoda na internetu** — Open Food Facts, prvo proizvodi iz Srbije
- **Tablica namirnica** — oko 350 namirnica i jela sa domaćeg tržišta (hleb i pecivo, meso i suhomesnato, domaći sirevi, voće, povrće, Plazma, Eurokrem, Smoki, domaća jela…), radi i bez interneta; komadi i porcije (1 jaje, 1 kriška, 1 kašika…)
- **Moji recepti** 📖 — složi jelo od sastojaka, upiši broj porcija (i po želji težinu gotovog jela) i dodaj porciju jednim dodirom; recepti su lični — čuvaju se na tvom uređaju i na tvom Google Drive-u
- **Šabloni obroka** 📋 — sačuvaj obrok koji često jedeš i dodaj ga ceo odjednom; „Ponovi ceo jučerašnji dan“
- **Moje namirnice i omiljene** ⭐, nedavno korišćeno, **brzi unos** samo kalorija (može i da se izmeni)
- **Očitavanje tabele sa pakovanja** 📷 — slikaj „Nutritivne vrednosti“, označi tabelu prstom i aplikacija upiše kalorije i nutrijente (latinica, ćirilica i mešano, više jezika)
- **Fizička aktivnost** 🏃 — šetnja, trčanje, bicikl, teretana…; potrošene kalorije se po želji dodaju dnevnom cilju
- **Post 16:8** ⏱️ — tajmer isprekidanog posta (12–20 h)
- **Podsetnici** 🔔 — za obroke koje još nisi upisao i za vodu
- **Dnevni cilj** — računa se iz pola, godina, visine, težine, aktivnosti i cilja (mršavljenje / održavanje / dobijanje, formula Mifflin-St Jeor); raspodela makronutrijenata po izboru; može i ručno
- **Voda** 💧 i **težina** ⚖️ sa grafikonom i BMI
- **Napredak** — kalorije po danima (7 / 14 / 30 dana), prosečni makronutrijenti, odakle je došlo najviše kalorija; **izveštaj za deljenje** (Viber, WhatsApp, e-pošta)
- **Google Drive sinhronizacija** ☁️ — isti podaci i podešavanja (profil, ciljevi, izgled, podsetnici) na svim tvojim uređajima
- **Rezervna kopija** — napravi / vrati jednim dugmetom; izvoz dnevnika za Excel (CSV)
- **Podrži autora** ☕ — aplikacija je besplatna; donacija za kafu (broj računa i IPS QR kod)
- **Izgled** — tamna, svetla ili automatska tema, boja akcenta

## Instalacija

Aplikacija se instalira direktno iz pregledača, bez prodavnice aplikacija.

### Android
1. Otvori https://gembirdt-bit.github.io/atmos-ishrana/ u **Chrome-u**.
2. U meniju (⋮) izaberi **Instaliraj aplikaciju** ili **Dodaj na početni ekran**.

### Windows
1. Otvori adresu u **Chrome-u** ili **Edge-u**.
2. Klikni ikonu za instalaciju u adresnoj traci (ili meni → **Instaliraj Atmos Ishrana**).

### iPhone / iPad
1. Otvori adresu u **Safari-ju**.
2. Dodirni **Podeli** → **Dodaj na početni ekran**.

Za skeniranje barkoda aplikacija traži dozvolu za kameru.

## Google Drive sinhronizacija

1. U aplikaciji otvori **Podešavanja → ☁️ Google Drive → Poveži Google Drive**.
2. Prijavi se svojim Google nalogom i odobri pristup.
3. Na drugom uređaju uradi isto sa **istim** Google nalogom — podaci se spajaju i od tada su isti na oba uređaja.

Podaci se čuvaju u fajlu „Atmos Ishrana — podaci.json“ na tvom Google Drive-u. Aplikacija vidi samo taj svoj fajl.

## Napomena

Vrednosti su okvirne i ne zamenjuju savet lekara ili nutricioniste. Podaci o proizvodima: © doprinosioci Open Food Facts, licenca ODbL.

## Verzije

### 1.4
- Online pretraga preko novog Open Food Facts servisa (Search-a-licious), stari search.pl kao rezerva, ponovni pokušaj kad je server preopterećen
- Pretraga tablice po rečima („stark krem bananica“ nalazi Bananicu), domaći proizvodi sa proizvođačem u nazivu

### 1.3
- Ažuriranje: nova verzija stiže odmah pri otvaranju (bez interneta radi iz memorije), traka „Stigla je nova verzija — Ažuriraj“, dugme „Proveri ažuriranje“ u Podešavanjima → O aplikaciji
- „Iz galerije“ za očitavanje tabele i za sliku barkoda (više se ne otvara kamera)

### 1.2
- Pouzdanije očitavanje tabele sa pakovanja: latinica, ćirilica i mešano (srpski, makedonski, albanski, engleski…), nazivi u dva reda, ispravka čestih grešaka (g→9, izgubljen zarez), provera po kalorijama, više prolaza
- Označavanje tabele prstom i okretanje slike pre očitavanja
- Sinhronizacija profila i podešavanja (težina, visina, ciljevi, post, izgled, podsetnici); novi uređaj preuzima podatke sa Drive-a umesto da ih pregazi
- Baza proširena na oko 350 namirnica sa domaćeg tržišta

### 1.1
- Recepti, šabloni obroka, ponavljanje celog dana
- Fizička aktivnost, post 16:8, podsetnici, izveštaj za deljenje
- Očitavanje nutritivne tabele sa pakovanja, ponuda za instalaciju
- Dugme „nazad“ na Androidu zatvara prozor umesto aplikacije; izmena brzog unosa

### 1.0
- Dnevnik, tablica namirnica, skeniranje barkoda, Open Food Facts, Google Drive

## Privatnost

Nema naloga, servera ni praćenja. [Politika privatnosti](https://gembirdt-bit.github.io/atmos-ishrana/privatnost.html) · [Uslovi korišćenja](https://gembirdt-bit.github.io/atmos-ishrana/uslovi.html)

## Tehnička podrška

E-pošta: **vasserviserbgd@gmail.com**

## Autor

**Gemb-Bit Željko Ilić** · [Sve Atmos aplikacije](https://gembirdt-bit.github.io/)

Aplikaciju možeš slobodno da koristiš. Ako praviš svoju verziju (clone), ostavi link ka autoru.
