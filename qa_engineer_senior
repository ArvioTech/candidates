# Zadání pro pozici Senior QA Engineer

## Kontext

Jsme malý agilní tým. Releasujeme v tuto chvíli cca 1x týdně, rádi bychom klidně i častěji. Jedním z našich produktů je **Dovolená za Benefity**.

Jedná se o multiproduct aplikaci s:
- Několika jazykovými mutacemi
- Více variantami, které vypadají podobně
- Kompletně vizuálně odlišným whitelabelem

**Odkazy na podobné varianty produktu:**
- Varianta 1: https://www.dovolena-za-benefity.cz/
- Varianta 2: https://www.wakacje-za-benefity.pl/
- Whitelabel: pouze držte na paměti, že existuje a v budoucnu budeme chtít také pokrýt testy.

**O týmu (pouze vývojové role):**
- 3 backend vývojáři
- 2 frontend vývojáři
- 1 manuální tester (50% pracovní doby)

Hledáme **QA seniora**, který bude:
- Posílením našeho QA týmu
- V budoucnu řídit tým několika QA engineerů
- Aktivně využívat AI nástroje
- Nastavovat procesy a automatizaci

## Úkoly

V rámci tohoto výběrového řízení vypracuješ dva nezávislé úkoly. Rozložení času mezi těmito dvěma úkoly je na tobě. Z naší strany je budeme hodnotit 50:50.

**Časový limit:** Maximálně 1 MD (man-day) - **TOTO JE TVRDÝ LIMIT**. Vybranému kandidátovi čas proplatíme.

V případě jakýchkoliv dotazů se ptej. Urči si vlastní deadline, do kdy zadání vypracuješ, a ten dodrž.

---

## Úkol 1: Strategický plán QA

### Zadání
Napiš dokument (cca 2 strany), jak bys nastavil QA v naší firmě v horizontu **6 měsíců**.

### Co nás zajímá
- Jak bys prioritizoval jednotlivé kroky v prvních 6 měsících?
- Jaké nástroje a technologie bys zvolil a proč?
- Jak bys řešil specifika multiproduktu, whitelabelů a jazykových mutací?
- Jak vidíš rozdělení mezi manuální a automatizované testování?
- Jak bys zapojil vývojáře do QA procesu? (myslíme tooling i kulturu, zaměř se spíš na kulturu)
- Jak plánuješ využívat AI v QA procesech?
- Co bys chtěl mít hotové za 3 měsíce a co za 6 měsíců?

**Poznámka k whitelabelu:** Drž na paměti, že whitelabel je vizuálně velmi odlišný od standardních variant a v budoucnu jich může být víc. Zajímá nás, jak by tento fakt ovlivnil tvůj přístup k psaní a organizaci testů.

### Formát
Svobodná forma, důležitá je jasnost myšlenek a praktičnost návrhu. Klidně použij AI k vypracování, pokud ti pomůže lépe formulovat myšlenky.

---

## Úkol 2: Praktická implementace v Playwrightu

### Zadání
Ve spolupráci s AI vytvoř set automatizovaných testů v **Playwrightu**, které pokryjí **náš produkt Dovolená za Benefity**:

#### Happy Path
Nákup ubytování s kombinací:
- Použití voucheru (validní kód ti poskytneme)
- Platba Pluxee
- Platba převodem

**Poznámka:** Polský produkt nemá platební metodu Pluxee - zde použij pouze voucher + převodem. Zajímá nás, jak tento rozdíl vyřešíš.

**Důležité:** Během testu pokryj co nejvíc features produktu. Chceme vidět, že jeden test kontroluje více věcí v každém kroku cesty.

**Výzva:** Jednou z výzev, kterou budeš muset vyřešit, je jak získáš správný booking link. Tento problém je součástí úkolu a chceme vidět tvé řešení.

#### Unhappy Path 1
Nákup produktu, který nelze zakoupit online.
- https://www.booking.com/Share-FY8kPf -> tento objekt nelze platit online

#### Unhappy Path 2
Pokus o rezervaci více pokojů, než je počet dospělých, pro které nakupujeme.

#### Unhappy Path 3
Použití neplatného voucheru při checkoutu - mělo by zobrazit chybovou hlášku.

### Technické požadavky
- Framework: **Playwright** (povinně)
- Testy musí skutečně fungovat proti live produktu (odkazy výše)
- Produkt je veřejný, nepotřebuješ credentials
- Řeš rozdíly mezi variantami (Pluxee platba vs. bez ní) - způsob řešení je na tobě, ale je pro nás důležitý
- Spuštění pouze lokálně (bez CI/CD setup)
- Reporting: stačí Playwright default report
- Kód musí být čitelný a maintainovatelný

### Co odevzdej
1. GitHub repository s funkčním kódem testů
2. README s:
   - Instrukcemi jak spustit
   - Popisem struktury a architektury testů
   - Popisem jak jsi využil AI v procesu tvorby
   - Stručnou reflexí (3-5 vět) - co bys dělal jinak, pokud bys měl víc času

### Hodnotíme
- Kvalitu a strukturu kódu
- Dobrý základ pro budoucí rozšiřitelnost
- Řešení rozdílů mezi variantami produktu
- Schopnost efektivně využít AI
- Praktičnost řešení pro reálné nasazení

---

## Co nám pošli

1. Strategický dokument (PDF/Markdown)
2. GitHub repository s testy a README

---

## Důležité poznámky

- Ptej se, pokud ti cokoliv není jasné
- **1 MD je skutečné maximum** - raději odevzdat méně, ale v limitu
- Očekáváme aktivní využití AI - zajímá nás, jak s ním umíš pracovat
- Pokud tě vybereme, čas ti proplatíme
- **Pokud narazíš na nejasnost:** Udělej rozumné rozhodnutí a zdokumentuj ho v README. Chceme vidět tvůj problem-solving a komunikační schopnosti.
