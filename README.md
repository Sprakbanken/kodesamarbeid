# Kodesamarbeid

Eksempel på arbeidsløype for å samarbeide om kode så enkelt og smertefritt som mulig.

## Opprett en egen gren 

Det er flere måter å opprette en gren på, fra terminalen, i nettleseren, eller i editoren. 
Vi starter med å opprette grena lokalt, jobbe lokalt, og deretter dytte alt til repoet på github.

```shell
git switch -c min-nye-gren
```

## Gjør endringer i repoet

> 👍 **Tommelfingerregel:**
>
> - Skriv store issues som dekker så mye som mulig, så mest mulig blir fikset på én gang
> - Lag store commiter
> - Opprett store PR-er som løser mange små problemer i så mange filer som mulig

## Commit-meldinger: Hva bør de inneholde? 

En commit-melding er ideelt sett en kort beskrivelse av hvordan koden har endret seg siden siste commit.

Meldingen er gjerne skrevet i imperativ, 
slik at commit-historikken kan leses som en liste med kommandoer som utføres av commitene meldingene hører til.

**Eksempel:**

```shell
git add README.md
git commit -m "Legg til instruksjoner i README slik at andre kan følge samme arbeidsløype."
``` 

> 🔗 NAV har en fin guide til commit-meldinger: https://github.com/navikt/offentlig/blob/main/guider/commit-meldinger.md

## Lag en pull request (PR)

En PR er en fin måte å introdusere kodeendringer fra én gren inn til en hovedgren i et repo som flere samarbeider på.

## Ressurser 

- https://ohshitgit.com/



