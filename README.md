# Sandėlio komplektavimas – PWA

Paprasta lietuviška sandėlio komplektavimo programėlė telefonui.

## Funkcijos
- Prekės įvedimas skenuojant barkodą (jei naršyklė palaiko BarcodeDetector) arba ranka.
- Rankinis barkodo įvedimas visada prieinamas.
- Prekės žymė / pavadinimas ir kiekis (galimi dešimtainiai kiekiai).
- To paties barkodo kiekio didinimas, redagavimas, šalinimas.
- Automatinis išsaugojimas telefono atmintyje.
- Komplekto peržiūra, kopijavimas į iškarpinę ir sąrašo išvalymas.
- Service Worker išsaugo programėlę naudojimui neprisijungus.

## Publikavimas
Saugykla publikuojama per GitHub Pages. Vieną kartą atidaryk Settings → Pages ir skiltyje Build and deployment → Source pasirink GitHub Actions. Po to kiekvienas pakeitimas automatiškai publikuos naują versiją.

Publikavimo adresas: https://regimantaslemezis-stack.github.io/SandelioKomplektavimas/

## Įdiegimas Android telefone
1. Atidaryk publikavimo adresą per Chrome.
2. Pasirink Įdiegti programą (arba Chrome meniu → Įdiegti programą / Pridėti prie pagrindinio ekrano).
3. Pirmą kartą atidaryk programėlę turėdamas internetą, kad ji išsisaugotų telefone.
4. Vėliau ji veiks ir be interneto.

Kolegoms perduok tą patį publikavimo adresą. Kiekvieno žmogaus komplektas saugomas tik jo telefone.

## Svarbu
- Kamera barkodui skaityti veikia tik saugiame HTTPS adrese ir tik naršyklėse, kurios palaiko BarcodeDetector. Jei kamera nepalaikoma, barkodą galima įvesti ranka.
- Programėlė nesiunčia prekių sąrašo į serverį.
- Išvalius naršyklės / programėlės duomenis, išsaugotas komplektas gali būti prarastas.