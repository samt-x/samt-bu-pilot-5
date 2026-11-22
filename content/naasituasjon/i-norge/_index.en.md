---
id: 2d9970b2-37db-4ed5-8153-02097f36c46e
title: "In Norway"
linkTitle: "In Norway"
weight: 10

---

{{< i-arbeid >}}

The identifiers and common solutions that an education ID must relate to in Norway.

## The National Population Register

The National Population Register (Folkeregisteret) shall enable secure, correct and efficient registration of basic personal data and of who is resident in Norway. Everyone who is required to register gets a unique identification number. The register has two:

- **National identity number** (fødselsnummer) is assigned at birth or when a person settles in Norway.
- **D number** is assigned to persons who do not meet the conditions for a national identity number, for example with a valid residence permit. It requires a stay in Norway of six months or more.

The National Population Register has no solution for persons who will be here for less than six months, or for the period before the D number is assigned.

The current number series are running out. The Storting has adopted new number series from 2032. Existing numbers remain valid, but all systems must be able to read the new ones.

## Auxiliary identifiers in different sectors

Many sectors need an auxiliary identifier for persons who are not in the National Population Register, either while waiting for registration or because they do not qualify.

| Identifier | Used for |
|---|---|
| Fictitious identity number | Locally created, unofficial number for registering persons in local case management systems |
| S number (Snr) | National number in higher education for students, researchers and employees without a national identity number or D number. The permission from the Directorate of Taxes requires that the number is not communicated to the user |
| H number and common auxiliary number | The health sector. The H number is internal to the organisation, the common auxiliary number is national |
| DUF number | The Norwegian Directorate of Immigration's number for applicants for asylum or a residence permit. Registered in the National Population Register as the immigration authorities' identification number |

See also [Other sectors](/en/pilotering/pilot-5/naasituasjon/andre-sektorer/).

## Feide

Feide is the national solution for login and data sharing in education and research. The Feide identity is bound to the organisation that issued it. Pupils who move between school owners, for example from one municipality to another or from lower secondary to upper secondary school, lose the old Feide identity and get a new one. The same applies to transitions between higher education programmes, and to student teachers who need access to the systems of their placement school.

A person register would make it possible for Feide to provide a person-centric identity, which identifies the person regardless of which school or institution they belong to. This can be done in two ways: one education eID that the person uses throughout their life, or Feide using the register to translate between identities, so that the user is recognised even if the eID is different. The first is a larger change, the second can be introduced gradually.

## MinID, ID-porten and eIDAS

MinID is the public eID in ID-porten and has a lower security level than the commercial alternatives, such as BankID. The plan for a state eID at a high level linked to the national ID card was shelved after a spending review in 2019. Instead, the state relies on commercial actors to issue eIDs at a high level.

ID-porten has three mechanisms that are relevant for users without a national identity number or D number:

- **eIDAS login** lets residents of the EU and EEA log in with their national eID. If the person has a national identity number or D number, and the country sends the same identifier as the one in the National Population Register, the login is linked to it. Otherwise the user is logged in without a Norwegian identifier, and the service must handle this itself.
- **Temporary login without a national identity number** was a solution from the COVID-19 pandemic in 2020, with machine reading of passports and facial recognition. It has been discontinued.
- **Pseudonymised login** is used in limited contexts, and can be a building block if an education ID is to be used without the identifier being shown to the service.

The important distinction: MinID and ID-porten solve authentication, not identification. An education ID solves an identification need, and can use ID-porten for authentication without changing this distinction.

## The Diploma Portal and the National Diploma Database

The Diploma Portal (Vitnemålsportalen) makes diplomas and results available, and shall prevent the use of forged diplomas. It was launched in 2017, covers universities and university colleges, and is to be extended to upper secondary schools and vocational colleges. Sikt is the data controller. Users can share results themselves with a link, through a recruitment system or as a signed PDF. The portal is based on EMREX.

The portal only stores the national identity number or D number and the institution's identity data. Persons without such numbers therefore have no results in the portal.

The National Diploma Database (NVB) has digital copies of most upper secondary school diplomas from the year 2000 onwards. The Norwegian Universities and Colleges Admission Service (Samordna opptak) uses them to assess applications and calculate points. The copies are in principle not valid documentation, but work is under way to change this. Sikt is also working on including diplomas from vocational colleges and individual results, and in the long term wants the NVB to cover the whole educational pathway.

## Felles IAM

Felles IAM is identity and access management for universities and university colleges. 13 institutions use it, and the goal is for all of them to adopt it. Felles IAM matches personal data from authoritative sources and gives each person one nationally unique, person-centric identifier (UH-ID) that follows the person regardless of institution and role.

Duplicates are prevented because all identification is done against one common person register. Source data are matched first on strong identifiers (national identity number, D number, S number, passport number with country code) and then on email and mobile number. Persons without a Norwegian national identity number get a UH-ID and access on an equal footing with others.

UH-ID is already used as the European Student Identifier (ESI) for students who need it, regardless of institution. Felles IAM is thus a national lookup point for identification in higher education, but does not cover the other levels of education.
