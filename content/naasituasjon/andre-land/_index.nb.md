---
id: f7b0a85c-b7e6-4840-ad1d-62ad4f467e0d
title: "Andre land og EU"
linkTitle: "Andre land og EU"
weight: 30
lastmod: 2026-11-22T23:53:35+01:00
last_editor: Erik Hagen

---

{{< i-arbeid >}}

Hvordan de nordiske landene og Nederland identifiserer personer i utdanning, og hvilke identifikatorer som finnes på europeisk nivå.

Kartleggingen bygger på offentlig tilgjengelige primærkilder, i hovedsak forvaltningsorganenes egen dokumentasjon og lovtekster, supplert med offisielle nyhetssaker. Piloten har ikke vært i direkte kontakt med forvaltningsorganene i landene, så opplysningene bør bekreftes før de legges til grunn for beslutninger.

## Finland

Finland er det eneste nordiske landet med en egen utdanningsid. **Studentnummeret** (oppijanumero) er en permanent identifikator for personen i utdanningsforvaltningens registre. Teknisk er det en OID med løpenummer og kontrollsiffer, ikke et format som ligner personnummer. Registeret føres av Utbildningsstyrelsen i tjenesten KOSKI, og nummeret tildeles automatisk gjennom tilkoblede tjenester som søknad, barnehageregisteret Varda og høyskolenes grensesnitt. Fra 2022 er det generell identifikator i utdanningsforvaltningen, også for lærere.

Ordningen dekker personer uten finsk personnummer, men ikke uten problemer. Uten treff i befolkningsregisteret må en saksbehandler identifisere personen manuelt. For personer uten personnummer lages det en ny identitet hver gang grunnopplysningene registreres på nytt, og duplikatene må slås sammen manuelt. Får personen senere personnummer, må de to identitetene også slås sammen manuelt.

## Sverige

Sverige har ingen egen utdanningsid. Forskriften om studieregistre ved universiteter og høyskoler krever navn og personnummer, eller et nummer som er unikt for studenten ved lærestedet. Kravet er altså bare lokal unikhet.

For personer uten personnummer finnes samordningsnummer hos Skatteverket, med tre identitetsnivåer fra 2023, men kommuner og skoler kan ikke be om det. Det felles studiesystemet Ladok lager lokale midlertidige personnumre, og byttet til ekte personnummer gjøres manuelt. Universitetskanslersämbetet avviste i 2023 et samlet nasjonalt studieregister, med personvern som begrunnelse.

Det nærmeste Sverige har til en personsentrisk identitet, er eduID.se fra Sunet, en identitetstjeneste som gjelder før, under og etter studiene, og som kan verifiseres med reisedokument for personer uten personnummer. Den er en identitetstjeneste, ikke et register.

## Danmark

**Unilogin** er en nasjonal digital identitet for elever, foreldre og ansatte fra dagtilbud gjennom hele grunnopplæringen, og følger barnet ved skolebytte. Den krever CPR-nummer og dekker ikke høyere utdanning, der den fødererte løsningen WAYF brukes. Unilogin løser altså skifte av skoleeier, men ikke personer uten offisielt nummer.

Danmarks svar på personer uten nummer ligger i folkeregisteret: Udlændingestyrelsen tildeler **administrative CPR-numre** ved første oppholdstillatelse, blant annet til flyktninger, familiegjenforente og asylbarn i skolen. Det er ordinære CPR-numre som personen beholder, så ingen overgang fra midlertidig til permanent nummer må automatiseres. Det krever opphold over tre måneder.

Erstatningspersonnumre er noe annet: de lages av virksomhetene selv, uten sentral oversikt eller avstemming mot et senere CPR-nummer. Utenlandske studenter får gjerne et slikt nummer fra universitetet og må selv melde fra hvis de senere får CPR-nummer.

## Island

Island har ingen egen utdanningsid. Kennitala tildeles bredt og raskt, også til studenter fra land utenfor EØS som del av oppholdstillatelsen. Et sentralt elevregister ble tatt i bruk i mars 2026 og forutsetter kennitala. Hvordan elever uten kennitala håndteres, er ikke dokumentert i kildene.

## Nederland

Alle innbyggere har et personnummer (BSN). De som ikke har det, får et lovregulert reservenummer som tildeles sentralt av DUO, som også eier registrene over elever og studenter, ett per utdanningsnivå. I grunn- og videregående opplæring og yrkesopplæring brukes ECK-iD, og i høyere utdanning tilbyr SURF en eduID.

## Europeisk nivå

Ingen europeisk identifikator gir en livslang, personsentrisk utdanningsid å bygge videre på:

- **European Student Identifier (ESI)** er navet i Erasmus Without Paper og det europeiske studentbeviset. Den skal være varig og globalt unik, men utstedes og forvaltes av lærestedet.
- **EUDI-lommeboken** (forordning (EU) 2024/1183) skal tilbys i alle medlemsland innen utgangen av 2026, og rommer både personidentifikasjon og attesterte opplysninger, som vitnemål. Storskalapiloten DC4EU, der Norge deltok, testet digitale vitnemål.
- **European Learning Model og Europass Digital Credentials** bygger på W3C Verifiable Credentials.
- **EMREX og ELMO** er et desentralisert nettverk for utveksling av resultater over landegrensene. Vitnemålsportalen er norsk kontaktpunkt.

Ingen europeisk ramme krever eller anbefaler en nasjonal livslang id for lærende. Hva de nye europeiske reglene krever av en norsk løsning, står under [Framtidige krav](/pilotering/pilot-5/loesningsvalg/framtidige-krav/).
