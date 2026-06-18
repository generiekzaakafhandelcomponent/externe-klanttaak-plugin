# Release notes

Overzicht van wijzigingen per versie van de Externe Klanttaak-plugin.

## 3.0.1
Plugin ondergebracht in een eigen repository met voorbeeldapplicatie en aparte documentatie, inclusief synchronisatie met de monorepo, build- en frontend-fixes en valtimo-configurator-metadata.

## 1.0.2
Geen foutmelding meer bij onbekende verwerker-taak-ID's: pogingen tot afhandeling van taken die niet bij de huidige gzac-instantie horen worden voortaan gelogd in plaats van een exception te veroorzaken.

## 1.0.1
Correcties op de Externe Klantaak 1.1.x-specificatie: `koppeling.uuid` hernoemd naar `koppeling.value` en `verloopdatum` aangepast van `LocalDate` naar `LocalDateTime`.

## 1.0.0
Eerste publieke release: externe klanttaken beheren via ZGW.
