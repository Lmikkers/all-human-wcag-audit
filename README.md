> _Fork_ deze deeltaak en ga aan de slag. De instructie vind je in: [docs/INSTRUCTIONS.md](https://github.com/fdnd-task/all-human-wcag-audit/blob/main/docs/INSTRUCTIONS.md)

# WCAG Audit 

Doe een WCAG test op een bestaande website en rapporteer daarover.

## MHC Lelystad

Ik heb de website MHC Lelystad getest. MHC Lelystad is een hockeyvereniging en op de website vind je daar meer informatie over. Je kan lid worden, je kan speelschema's bekijken en meer informatie vinden over de club. 

<img width="500" src="https://github.com/Lmikkers/all-human-wcag-audit/assets/94455811/b37b840f-7f2b-4fa5-a77e-91a987e5d37f">


## Lighthouse Accessibility testresultaat.
<img width="750" alt="Scherm­afbeelding 2023-10-16 om 11 49 39" src="https://github.com/Lmikkers/the-client-website/assets/94455811/d98dcbff-fc4a-4111-a78d-0871ae3cce1c">

Schrijf een samenvatting van de testbevindingen.

***Belangrijkste bevindingen***

* De images hebben geen alt tekst
  * `<img alt="tekst over de afbeelding">`
* De links hebben geen herkenbare naam
  * Dit zou ik oplossen door de linkjes een naam te geven die daarbij hoor en geen lees meer bv te gebruiken.
* Select elementen hebben geen gekoppelde label
  * Dit gaat in dit geval over de formulieren `<form>`, deze zou ik dan een `<form name="">` geven.
* De Headers zijn niet in aflopende volgorde
  * Dit zou ik oplossen door ze op goeie volgorde neer te zetten: h1, h2, h3, h4, h5

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
