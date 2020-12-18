---
title: Inntak og vurdering 
linktitle: Inntak og vurdering
type: book
date: "2019-05-05T00:00:00+01:00"
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
diagram: true
---

Henvisning sendt til Klinikk for psykisk helse skal vurderes av inntaksteam/vurderingsteam i den kliniske enhet som pasienten sorterer inn under.

Det vil si at henvisning vurderes av et tverrfagligteam bestående av minst en psykologspesialist og psykiater.

Vurderinger gjøres med utgangspunkt i Prioriteringsforskriften §§ 2 og 2a. Med bakgrunn i dette tildeles enten **rett til helsehjelp**, jmf. Pasient og brukerrettighetsloven § 2-1. Eller man vurderer at det **ikke foreligger behov for helsehjelp fra spesialisthelsetjenesten**. Vurdering med tilbakemelding til pasient skal gjøres innen 10 dager.

To punkter skal vurderes når rett til helsehjelp tildeles;

- Nytte av helsehjelpen

- Det skal være et rimelig forhold mellom kostnader og nytte

Der det innvilges rett til helsehjelp fra spesialisthelsetjenesten, kan dette være enten **rett til utredning** eller **rett til behandling**. Rett til behandling gis der man er sikker på pasientforløp. Rett til utredning når det er mer uavklarte forhold og usikkerhet rundt antatt diagnose og problemstilling.

Frist for oppstart skal settes. Fristen avhenger av vurderingen som gjøres av graden av alvorlighet.


## OCD team DPS Solvang

I de fleste tilfeller gir en tvangslidelse rett til helsehjelp fra spesialisthelsetjenesten, jmf. Prioriteringsveileder for psykisk helsevern for voksne.

Ved rett til helsehjelp vil rimelig ventetid være 3 mnd. Der det vurderes å foreligge rett til oppfølging ved spesialisthelsetjenesten, tildeles en behandler ved lokalt DPS.

Deretter foretas en sekundærhenvisning til OCD teamet ved DPS Solvang. Pasienten kalles inn til prescreening ved OCD teamet i løpet av ca 4 uker.

Behandling gis av et spesialisert OCD team, lokalisert ved DPS Solvang. Samarbeid med primærhelsetjenesten gjøres av behandler ved lokalt DPS.


## Oversiktsbilde - vurderinger og rettigheter

```mermaid
graph TD;
  A[Vurdering av henvisning] --> B(Rett til behandling)
  A[Vurdering av henvisning] --> C(Rett til utredning)
  A[Vurdering av henvisning] --> D(Ikke behov for helsehjelp fra spesialisthelsetjenesten)
  
  B(Rett til behandling) --> E[Pasientforløp annen tilstand]
  B(Rett til behandling) --> H[Pasientforløp tvangslidelse/OCD]
  C(Rett til utredning) --> F[Utredning av uavklart tilstand]
  C(Rett til utredning) --> G[Avklare det uavklarte - avklare om det foreligger psykisk lidelse]
  G[Avklare det uavklarte - avklare om det foreligger psykisk lidelse] --> F[Utredning av uavklart tilstand]
  F[Utredning av uavklart tilstand] --> E[Pasientforløp annen tilstand]
  F[Utredning av uavklart tilstand] --> H[Pasientforløp tvangslidelse/OCD]
  F[Utredning av uavklart tilstand] --> D(Ikke behov for helsehjelp fra spesialisthelsetjenesten)
  G[Avklare det uavklarte - avklare om det foreligger psykisk lidelse] --> D(Ikke behov for helsehjelp fra spesialisthelsetjenesten)
  '''