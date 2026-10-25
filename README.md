# Budsjettkompis

En enkel budsjettapp for studenter, laget med vibe coding (AI-assistert koding).

## Hva og hvorfor
Mange studenter lever på studielån og deltidsjobb, og har lite oversikt over hvor pengene blir av i løpet av måneden. Budsjettkompis gjør det raskt å registrere inntekter og utgifter og se hvordan man ligger an mot et månedsbudsjett.

## Funksjoner
1. **Registrer transaksjoner**: inntekt eller utgift, med beløp, kategori, dato og beskrivelse. Feil input (tomt beløp, negativt beløp) gir en feilmelding.
2. **Månedsbudsjett**: en fremdriftslinje viser hvor mye av budsjettet som er brukt. Den blir gul over 80 % og rød over 100 %.
3. **Oversikt per måned**: sum inntekter/utgifter/saldo, utgifter per kategori som stolpediagram, og en filtrerbar liste der transaksjoner kan slettes. Man kan bla mellom måneder.

Data lagres lokalt i nettleseren (localStorage). Ingen innlogging, server eller personopplysninger.
Knappen «Last inn eksempeldata» fyller appen med realistiske tall for demo.

## Kjør appen
Åpne `index.html` i en nettleser. Ingen installasjon trengs.

## Hvordan AI ble brukt
- Ideen og funksjonslisten ble valgt sammen med AI (Claude) ut fra oppgaveteksten.
- All kode (HTML, CSS, JavaScript) ble generert av AI fra beskrivelser på naturlig språk.
- Testing: appen ble testet i nettleseren ved å legge til og slette transaksjoner, prøve ugyldig input, bytte måned, endre budsjett og laste siden på nytt for å sjekke at data blir lagret.

## Teknologi
Ren HTML, CSS og JavaScript i én fil. Støtter mørk modus og mobilskjerm.
