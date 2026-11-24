# Luwtewerf

Dit is het bronpakket voor een fictief woonproject aan een binnenhaven. Alle namen, woningen, prijzen en teksten zijn gemaakt voor deze proef. Gebruik de bestanden in een eigen kopie. De richtinzet is 26 uur binnen twee kalenderweken vanaf toewijzing.

## Wat vind je hier?

- `bron/woningstaat.csv` is de door de projectbeheerder vrijgegeven basis voor woonoppervlakte, prijs en status per woning.
- `bron/teksten.json` bevat de NL- en EN-redactieteksten en hun vrijgavestatus per taal. Het project en de woningcodes blijven in beide talen gelijk.
- `bron/releases.json` bevat de drie opeenvolgende releaseproeven en hun mutaties. Iedere proef start vanaf de expliciet genoemde basis. Aanpassingen onder `changes` overschrijven de bijbehorende velden voor die versie.
- `bron/redactienotities.md` bevat context en twee berichten die je moet wegen voordat je een claim overneemt.
- `media/situatie.svg` is een originele, schematische situatietekening voor de proef. Je mag die gebruiken of vervangen.

## Publicatieregels

De projectbeheerder beslist over feiten en noemt de woningen voor een release. De redacteur keurt per woning beide taalteksten goed. Een kandidaat-release met een ontbrekende goedkeuring of dubbele slug mag de vorige live-versie niet vervangen. Publiceer in beide talen dezelfde selectie. De variant met een fout mag je lokaal voor de redacteur laten zien.

Voor de publieke site telt wat het publicatieproces naar de publieke uitvoermap of CMS-export schrijft. Bezoekers mogen via pagina's, directe URL's, publieke JSON of sitemap uitsluitend de vrijgegeven selectie terugvinden. De fictieve bronbestanden mogen in je openbare oefenrepository staan. Een lokale conceptpreview volstaat.

## Overdracht

Voeg in de hoofdmap `README.md` voor de reviewer en `REDACTIE.md` voor de redacteur toe. Dit zijn de twee bestandschecks van het portaal. Volg voor het werk en de beoordeling de opdracht in het ACE-sollicitantenportaal.
