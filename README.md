ICA 05 Gruppe 2

vi har jobbet med dette sammen på en pc og derfor ble en bare en commit.
navn på deltakere:
Dyb Nikolai
Hassan Shiwan
Krossen Ella
Sandøy Benjamin
Thompson Sindre



ICA 05 har vi laget koden ved hjelp av hjelpelærere som viste oss martini og hjalp oss i klassen



Packages:

I denne koden bruker vi main package som importerer disse pakkene
Github.com/og-martini/martini
Github.com/martini-contrib/render
Io/ioutil
Log
Net/http
Strconv
Strings
Time

Vi bruker struct til å gruppere en kollektion av felt, dette er da nyttig for å gruppering av de dataene vi har brukt. Som f.eks  Name, Count, ServerIP, mapdata

Vi bruker martini til å kjøre main functionen vår som skal hente http.request og kjører vår template som er laget i golang.
På linje 47 har vi lagt til localhost porten som er da «1122»
På linje 53 så  har vi laget en annen function som kjører api som vi har brukt, til å lokalisere hvor «universitetene ligger» det er en api fra googlemaps.
Siste functionen vi har er bare for å telle hvor lenge serveren har vært oppe og går.

Dette er både mulig å kjøre localt og via nettsky. For å kjøre lokalt så skriver man localhost:1122
Og for å kjøre den på nettskyen så åpnet vi en port på ubuntu nettskyen vår og definerte en område som portlengeden kan være på. Etter det lastet vi opp filene til nettskyen, også ved hjelp ifconfig kunne vi finne ipadressen som vi brukte til å aksesere serveren.
For å kjøre den begynner man med å skrive go run server.go. når serveren kjører kan man gå på en nettleser og skrive inn ipadresse:1122.
