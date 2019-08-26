# studieschuld-verberger
Verbergt je studieschuld bij het inloggen op Mijn DUO

Werkt ook met mobiele weergave. Let op: als je in Mijn DUO op details klikt, krijg je je studieschuld alsnog wel te zien. Ook kan het zijn dat je elders het nog wel tegenkomt. Dit middel helpt enkel op de beginpagina van Mijn DUO.

## Instructies

1. Installeer de vanalles-blocker [uBlock Origin](https://github.com/gorhill/uBlock/#installation) als je dat nog niet hebt
2. Ga naar de instellingen van uBlock (klik op icoon, vervolgens voorkeurenicoon)
3. Navigeer naar tabblad "My filters" bovenin
4. Voeg deze regel toe: `mijn.duo.nl###bedrag_studieschuld_opbouwfase > .pull-right`

## Help, ik krijg mijn studieschuld alsnog te zien!

Excuses.

Het onverhoopt alsnog zien van je studieschuld kan komen doordat deze methode nog niet volledig is getest. Ook kan het zijn dat DUO hun site heeft bijgewerkt waardoor dit niet meer werkt.

Ben je technisch aangelegd, stuur alsjeblieft een pull/merge request.

Mocht het ernstige gevolgen hebben, praat erover met je naasten. Maak desnoods een afspraak met je huisarts, hij/zij kan je ook helpen.
