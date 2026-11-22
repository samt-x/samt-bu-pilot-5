---
title: "I Norge"
linkTitle: "I Norge"
weight: 10

---

{{< i-arbeid >}}

Identifikatorene og fellesløsningene en utdanningsid må forholde seg til i Norge.

## Folkeregisteret

Folkeregisteret skal legge til rette for sikker, korrekt og effektiv registrering av grunnleggende personopplysninger og av hvem som er bosatt i Norge. Alle registreringspliktige får et unikt identifikasjonsnummer. Registeret har to:

- **Fødselsnummer** tildeles ved fødsel eller bosetting.
- **D-nummer** tildeles personer som ikke fyller vilkårene for fødselsnummer, for eksempel ved gyldig oppholdstillatelse. Det krever opphold i Norge i seks måneder eller mer.

Folkeregisteret har ingen løsning for personer som skal være her kortere enn seks måneder, eller for tiden før D-nummeret er tildelt.

Dagens nummerserier er i ferd med å bli brukt opp. Stortinget har vedtatt nye nummerserier fra 2032. Eksisterende numre er fortsatt gyldige, men alle systemer må kunne lese de nye.

## Hjelpeidentifikatorer i ulike sektorer

Mange sektorer trenger en hjelpeidentifikator for personer som ikke er i Folkeregisteret, enten i påvente av registrering eller fordi de ikke kvalifiserer.

| Identifikator | Brukes til |
|---|---|
| Fiktivt fødselsnummer | Lokalt laget, uoffisielt nummer for å registrere personer i lokale saksbehandlingssystemer |
| S-nummer (Snr) | Nasjonalt nummer i høyere utdanning for studenter, forskere og ansatte uten fødselsnummer eller D-nummer. Skattedirektoratets tillatelse forutsetter at nummeret ikke formidles til brukeren |
| H-nummer og felles hjelpenummer | Helsesektoren. H-nummer er internt i virksomheten, felles hjelpenummer er nasjonalt |
| DUF-nummer | Utlendingsdirektoratets nummer for søkere om asyl eller oppholdstillatelse. Registreres i Folkeregisteret som utlendingsmyndighetenes identifikasjonsnummer |

Se også [Andre sektorer](/pilotering/pilot-5/naasituasjon/andre-sektorer/).

## Feide

Feide er den nasjonale løsningen for innlogging og datadeling i utdanning og forskning. Feide-identiteten er bundet til organisasjonen som har utstedt den. Elever som flytter mellom skoleeiere, for eksempel fra en kommune til en annen eller fra ungdomsskole til videregående, mister den gamle Feide-identiteten og får en ny. Det samme gjelder ved overganger mellom høyere utdanninger, og for lærerstudenter som skal inn i praksisskolens systemer.

Et personregister ville gjøre det mulig for Feide å gi en personsentrisk identitet, som identifiserer personen uavhengig av hvilken skole eller institusjon vedkommende tilhører. Det kan gjøres på to måter: én kunnskaps-eID som personen bruker gjennom hele livet, eller at Feide bruker registeret til å oversette mellom identiteter, slik at brukeren gjenkjennes selv om eID-en er forskjellig. Den første er en større endring, den andre kan innføres gradvis.

## MinID, ID-porten og eIDAS

MinID er den offentlige eID-en i ID-porten og har et lavere sikkerhetsnivå enn de kommersielle alternativene, som BankID. Planen om en statlig eID på høyt nivå knyttet til det nasjonale ID-kortet ble skrinlagt etter en områdegjennomgang i 2019. Staten satser i stedet på at kommersielle aktører utsteder eID på høyt nivå.

ID-porten har tre mekanismer som er relevante for brukere uten fødselsnummer eller D-nummer:

- **eIDAS-innlogging** lar innbyggere i EU og EØS logge inn med nasjonal eID. Har personen fødselsnummer eller D-nummer, og landet sender samme identifikator som står i Folkeregisteret, kobles innloggingen til det. Ellers logges brukeren inn uten norsk identifikator, og tjenesten må selv håndtere det.
- **Midlertidig innlogging uten fødselsnummer** var en løsning fra koronapandemien i 2020, med maskinlesing av pass og ansiktsgjenkjenning. Den er avviklet.
- **Pseudonymisert innlogging** brukes i avgrensede sammenhenger, og kan være en byggekloss hvis en utdanningsid skal brukes uten at identifikatoren vises for tjenesten.

Det viktige skillet: MinID og ID-porten løser autentisering, ikke identifikasjon. En utdanningsid løser et identifikasjonsbehov, og kan bruke ID-porten til autentisering uten at det endrer skillet.

## Vitnemålsportalen og Nasjonal vitnemålsdatabase

Vitnemålsportalen gjør vitnemål og resultater tilgjengelige, og skal hindre bruk av forfalskede vitnemål. Den kom i 2017, dekker universiteter og høyskoler, og skal utvides til videregående skoler og fagskoler. Sikt er behandlingsansvarlig. Brukeren kan selv dele resultater med lenke, gjennom et rekrutteringssystem eller som signert PDF. Portalen bygger på EMREX.

Portalen lagrer bare fødselsnummer eller D-nummer og institusjonens identitetsopplysninger. Personer uten slike numre har derfor ingen resultater i portalen.

Nasjonal vitnemålsdatabase (NVB) har digitale kopier av de fleste vitnemål fra videregående skole fra og med år 2000. Samordna opptak bruker dem til å vurdere og poengberegne søknader. Kopiene er i utgangspunktet ikke gyldig dokumentasjon, men det arbeides med å endre det. Sikt arbeider også med å ta inn vitnemål fra fagskoler og enkeltresultater, og ønsker på sikt at NVB skal dekke hele utdanningsløpet.

## Felles IAM

Felles IAM er identitets- og tilgangsstyring for universiteter og høyskoler. 13 institusjoner bruker den, og målet er at alle skal ta den i bruk. Felles IAM matcher personopplysninger fra autoritative kilder og gir hver person én nasjonalt unik, personsentrisk identifikator (UH-ID) som følger personen uavhengig av institusjon og rolle.

Dubletter forebygges ved at all identifikasjon skjer mot ett felles personregister. Kildedata matches først på sterke identifikatorer (fødselsnummer, D-nummer, S-nummer, passnummer med landkode) og så på e-post og mobilnummer. Personer uten norsk fødselsnummer får UH-ID og tilganger på lik linje med andre.

UH-ID brukes allerede som European Student Identifier (ESI) for studenter som trenger det, uavhengig av institusjon. Felles IAM er dermed et nasjonalt oppslagspunkt for identifikasjon i høyere utdanning, men dekker ikke de andre utdanningsnivåene.
