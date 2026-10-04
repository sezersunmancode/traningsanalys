# Träningsanalys

## Syfte

Träningsanalys är ett Pythonprojekt som analyserar träningsdata från
styrketräning.

Programmet läser in träningsdata från en CSV-fil och analyserar bland annat:

- träningsvolym
- antal träningspass
- högsta vikt
- genomsnittlig vikt
- viktutveckling över tid
- träningsfrekvens

Resultatet presenteras både som statistik och med visualiseringar.

Syftet med projektet är att visa hur Python kan användas för att läsa in,
bearbeta, analysera och visualisera data.

Projektet har koppling till AI- och datautveckling eftersom datahantering,
databearbetning, analys och visualisering är viktiga delar av arbete med
datadrivna system och AI-lösningar.

## Metod

Programmet använder en CSV-fil som datakälla. Datan läses in med
Pythons standardbibliotek `csv` och omvandlas till lämpliga datatyper
innan den analyseras.

Programmet använder bland annat:

- variabler och olika datatyper
- listor och dictionaries
- if-satser och loopar
- egna funktioner med parametrar och returvärden
- `try` och `except` för felhantering
- klasser och objektorienterad programmering
- arv mellan klasser
- `datetime` för att hantera datum
- `matplotlib` för visualisering
- CSV för att läsa och spara data

Träningsvolymen beräknas genom att multiplicera vikt, antal repetitioner
och antal set.

Programmet kan analysera en specifik övning och beräkna antal pass,
högsta vikt och genomsnittlig vikt. Det kan även beräkna träningsvolym
per övning och träningsfrekvens.

Resultaten visualiseras med diagram som visar bland annat total
träningsvolym per övning och viktutveckling över tid.

Projektet innehåller även objektorienterad programmering. Klassen
`Traningspass` fungerar som basklass och `Styrkepass` ärver från den.
Det gör det möjligt att återanvända gemensamma egenskaper och metoder
samtidigt som en specialiserad typ av träningspass kan innehålla
ytterligare information.

## Resultat

Programmet analyserade totalt 12 träningspass under perioden
2026-09-01 till 2026-09-23.

Den totala träningsvolymen var 18 382,5 kg.

Fördelningen av träningsvolym per övning blev:

- Bänkpress: 7 312,5 kg
- Knäböj: 6 600 kg
- Marklyft: 4 470 kg

Bänkpress hade högst total träningsvolym.

Analysen av Bänkpress visade:

- antal pass: 5
- högsta vikt: 80 kg
- genomsnittlig vikt: 75 kg

Viktutvecklingen i Bänkpress ökade från 70 kg till 80 kg under
den analyserade perioden.

Träningsperioden var 22 dagar och den genomsnittliga
träningsfrekvensen var cirka 3,82 pass per vecka.

Resultaten visas även visuellt med Matplotlib. Ett diagram visar
träningsvolymen per övning och ett annat visar viktutvecklingen
för Bänkpress över tid.

Diagrammen gör det enklare att se skillnader mellan övningarna
och utvecklingen över perioden än om resultaten endast hade
presenterats som text eller siffror.

## Analys

Resultatet visar att träningsdata kan användas för att hitta mönster,
jämföra aktiviteter och följa utveckling över tid. I projektet kunde
vi bland annat se vilken övning som hade högst träningsvolym och hur
Bänkpress utvecklades under den analyserade perioden.

Projektet har en tydlig koppling till AI- och datautveckling eftersom
datadrivna system ofta behöver flera steg innan en AI-modell kan
användas. Data behöver samlas in, struktureras, kontrolleras,
bearbetas och analyseras.

I projektet används Python för att automatisera dessa steg. Programmet
läser in data från en CSV-fil, omvandlar datatyper, beräknar nya värden,
hanterar fel och presenterar resultatet visuellt.

Detta liknar delar av det arbete som en AI- eller datautvecklare kan
behöva göra i ett större system. Exempelvis kan en AI-utvecklare
behöva förbereda träningsdata innan den används för maskininlärning.
Om datan är felaktig eller dåligt strukturerad kan det påverka
resultatet från en framtida AI-modell.

Projektet visar därför flera grundläggande kompetenser som är relevanta
för en AI-utvecklare:

- läsa in och strukturera data
- kontrollera och omvandla datatyper
- bearbeta data med Python
- skapa återanvändbara funktioner
- använda objektorienterad programmering
- använda arv mellan klasser
- hantera fel med `try` och `except`
- analysera resultat
- visualisera data

Visualiseringarna med Matplotlib gör det enklare att upptäcka mönster
och förändringar. Stapeldiagrammet gör det möjligt att jämföra
träningsvolym mellan övningar medan linjediagrammet visar
viktutvecklingen över tid.

En möjlig vidareutveckling är att samla in betydligt större mängder
träningsdata och lagra informationen i en databas eller molntjänst.
Datan skulle då kunna behandlas automatiskt och användas som underlag
för mer avancerad analys.

På längre sikt skulle projektet kunna kompletteras med
maskininlärning för att exempelvis identifiera träningsmönster,
förutsäga utveckling eller ge personliga rekommendationer. En sådan
lösning skulle dock kräva mer data och noggrann utvärdering för att
resultaten ska bli tillförlitliga.

Projektet är därför inte en AI-modell i sig, utan ett exempel på den
datahantering och analys som kan fungera som grund för framtida
AI-lösningar.

## Relevanta certifikat

För en AI- eller datautvecklare är kunskaper inom molntjänster
relevanta eftersom AI- och datalösningar ofta körs i molnmiljöer.

### Microsoft Azure

Microsoft Azure erbjuder certifieringar inom bland annat molnteknik,
data och AI. Ett relevant certifikat är Microsoft Certified: Azure AI
Apps and Agents Developer Associate (AI-103).

Certifieringen fokuserar på att utveckla och distribuera AI-lösningar
med Python och Microsoft Foundry, inklusive generativ AI och
AI-agenter.

Kunskaper inom Azure skulle kunna användas för att vidareutveckla
det här projektet genom att exempelvis lagra träningsdata i molnet,
automatisera dataanalysen eller bygga AI-baserade funktioner ovanpå
den insamlade datan.

### AWS

AWS är en annan stor molnplattform som används inom data och AI.
Ett relevant certifikat är AWS Certified Machine Learning Engineer –
Associate.

Certifieringen uppdateras under 2026 till MLA-C02. Den nya versionen
omfattar bland annat maskininlärning, generativ AI, AI-agenter,
foundation models och LLM samt molnbaserade AI-lösningar med tjänster
som Amazon SageMaker AI och Amazon Bedrock.

Kunskaper inom AWS skulle kunna användas för att vidareutveckla det
här projektet genom att exempelvis flytta datalagringen från en lokal
CSV-fil till en molntjänst och automatisera dataanalysen.

Det skulle också vara möjligt att senare bygga AI-baserade funktioner
ovanpå träningsdatan, exempelvis för att upptäcka mönster eller ge
rekommendationer.

### Koppling till projektet

Projektet använder idag en lokal CSV-fil eftersom lösningen är
avsiktligt enkel och fokuserar på grundläggande Python och
dataanalys.

I ett större verkligt system skulle data kunna lagras i en
molntjänst och behandlas automatiskt. Därför är kunskaper inom
Azure eller AWS relevanta för en framtida AI-utvecklare.

Jag bedömer att Azure AI Apps and Agents Developer Associate är
relevant för projektets framtida utveckling eftersom projektet redan
arbetar med dataanalys och skulle kunna byggas ut med AI-baserade
funktioner och agenter.

## Reflektion

En styrka med projektet är att lösningen är relativt enkel men ändå
visar flera viktiga delar av Pythonprogrammering och dataanalys.
Jag valde att använda en CSV-fil som datakälla eftersom formatet är
enkelt att förstå och passar bra för projektets omfattning.

En annan fördel är att projektet är uppdelat i flera olika delar,
exempelvis datainläsning, analys, objektorienterad programmering och
visualisering. Det gör koden lättare att förstå och vidareutveckla.

En utmaning under projektet var att hantera data från CSV-filen
eftersom värden som läses in från en fil från början är text. Därför
behövde exempelvis vikt omvandlas till `float` och repetitioner och
set till `int`. Jag behövde även använda felhantering för att kunna
hantera saknade filer och ogiltiga numeriska värden.

Jag valde att använda klasser och arv eftersom kursen kräver
objektorienterad programmering, men också eftersom det ger en
struktur som skulle kunna användas om projektet byggs ut med fler
typer av träningspass.

Visualiseringarna med Matplotlib gjorde resultaten lättare att
tolka. Stapeldiagrammet visar skillnaden i träningsvolym mellan
övningarna medan linjediagrammet tydligt visar viktutvecklingen
i Bänkpress.

Om jag skulle utveckla projektet vidare skulle jag bland annat
använda en större datamängd och kunna lagra data i en databas eller
molntjänst. Jag skulle även kunna lägga till fler typer av analyser,
exempelvis utveckling per muskelgrupp och automatiserad upptäckt av
träningsmönster.

På längre sikt skulle projektet kunna utvecklas med AI för att
identifiera mönster i träningsdata och ge mer avancerade analyser.
Det skulle göra projektet mer direkt kopplat till AI-utveckling,
men jag valde att inte lägga till en AI-modell i grundversionen
eftersom fokus i projektet är att visa att jag själv förstår Python,
datahantering, analys och programmeringsstrukturen.

## Installation och körning

Projektet kräver Python 3 och biblioteket Matplotlib.

### 1. Klona projektet

Klona GitHub-repositoriet med:

`git clone https://github.com/sezersunmancode/traningsanalys.git`

Gå sedan in i projektmappen:

`cd traningsanalys`

### 2. Installera bibliotek

Installera projektets beroenden med:

`pip install -r requirements.txt`

### 3. Starta projektet

Öppna `main.ipynb` i Jupyter Notebook eller Visual Studio Code.

Kör notebookens celler uppifrån och ned för att:

- läsa in träningsdata från CSV-filen
- bearbeta och kontrollera datan
- beräkna träningsvolym
- analysera träningspassen
- skapa träningsobjekt med klasser
- beräkna träningsperiod och träningsfrekvens
- spara analyserad data
- skapa visualiseringar med Matplotlib

Projektet använder `training_data.csv` som ursprunglig datakälla.

De genererade resultaten sparas bland annat i:

- `analyserad_traningsdata.csv`
- `bankpress_utveckling.png`
- `traningsvolym_per_ovning.png`

## GitHub

Projektets källkod finns på GitHub:

https://github.com/sezersunmancode/traningsanalys
