---
draft: false
aliases:
  - Events
tags:
  - Lore
---
Coming soon...

``` mermaid
%%{init: { 'theme': 'neutral' }}%%
timeline
    title Events of Nyropa
    Before The Reckoning :
    +2500 BR <br> Settlers of the Shazahath Mountains : 1008 BR <br> The Lost City Founded : 823 BR <br> Porthca Founded : 813 BR <br> Brugrove Founded : 607 BR <br> Valonde Founded
	After The Reckoning : 000 AR <br> Isle of Black <br> Brugove become a Monarchy : 012 AR <br> First mention of 'Swiftbolt' : 213 AR <br> Current Day


```








``` mermaid
---
title: Events of Nyropa
---
stateDiagram-v2
	state "+2500 BR" as SM
	state "1008 BR" as LC
	state "823 BR" as PT
	state "813 BR" as BG
	state "607 BR" as VL
	state "00/00/000" as TR
	state "012 AR" as SW
	state "213 AR" as CD
    [*] --> SM
    SM : First Settlers of Shazahath Mountains
    SM --> LC
    LC : Lost City Founded
    LC --> PT
    PT : Porthca Founded
    PT --> BG
    BG : Brugrove Founded
    BG --> VL
    VL : Valonde Founded
    VL --> TR : The Great Forgotten War
    TR: Brugrove Monarchy
    TR: Isle of Black
    TR --> SW
    SW : First mention of 'Swiftbolt'
    SW --> CD
    CD : Current Day
    
    
```






``` mermaid
sequenceDiagram
	autonumber
	participant D as Date
	participant E as Event
	link E: Dashboard @ https://dashboard.contoso.com/alice
	link D: Dashboard @ https://dashboard.contoso.com/alice
    
    D->>E: +2500 BR First Settlers of Shazahath Mountains
    D->>E: 1008 BR Lost City Founded
    D->>E: 823 BR Porthca Founded
    D->>E: 813 BR Brugrove Founded
    D->>E: 607 BR Valonde Founded
    D->>E: The Great Forgotten War
    E-->E: Brugrove become a Monarchy<br/>
    E-->E: Isle of Black
    D->>E: 012 AR First mention of 'Swiftbolt'
    D->>E: 213 AR Current Day
    



```



