---
marp: true
author: Daniele Riccucci
paginate: true
class:
    - invert
style: |
    section {
        background-color: #53565A;
        font-size: 1.7em;
    }
    section.columns {
        p {
            columns: 2
        }
    }
    footer {
      font-size: 50%;
    }

    div.columns {
      display: grid;
      grid-template-columns: 1fr max-content;
      grid-gap: 10px;
      box-sizing: border-box;
      background-color: inherit;
      color: inherit;
      width: 100%;
      height: 100%;
      align-items: center;
      justify-content: center;
    }

    div.imgcols {
      display: grid;
      justify-content: center;
      align-items: center;
      grid-template-rows: [picture] 1.5fr [text] 1fr;
      grid-template-columns: [picture] 1.5fr [text] 1fr;
      grid-gap: 2%;
      width: 100%;
      height: 100%;
    }

    ul {
      padding-inline-start: 1em;
    }
    li {
      padding-inline-start: 0em;
    }
---

# Candidosi invasiva

---
# Intro

Paziente di 30 anni.

Diagnosi di LLA-B esordita con pallore cutaneo, astenia progressiva e febbre,  ricoverata per pancitopenia, sospetta polmonite e splenomegalia.

- già neutropenica all'esordio di malattia
- colonizzazione rettale da *Candida glabrata* I a caspofungina, S a micafungina ∴ profilassi con micafungina

Trattata con schema LAL1913 (induzione con prednisone 20 mg/m2 e ciclofosfamide, poi idarubicina ∧ vincristina ∧ PEG-asparaginasi ∧ desametasone).
Supportata con G-CSF.

---

# Caso clinico

<div class="columns">
  <div>
  Comparsa di febbre persistente a fine ciclo di CHT, non responsiva a trattamento empirico con vari antibiotici (PTZ, VAN, MER)

  Diagnostica:
  - RX torace negativo; HRCT torace: 3 aree di GG
  - BDG neg > 21.2 > 58.5 con GM negativo
  - emocolture neg > *Candida krusei* S ad echinocandine
  - Restanti esami microbiologici (EBV, CMV, Chlamydia, Mycoplasma, Ag urinari): negativi

  Iniziata terapia con voriconazolo EV (sospeso per rash cutaneo diffuso), escalato ad AmB (4 mg/kg/die) con rapida negativizzazione delle emocolture (4 giorni da inizio tp).
  </div>
<div>

Drug | MIC (mg/L) |
-----|:------:|
Anidulafungina | 0.03 |
Caspofungina | 0.12 |
Micafungina | 0.125 |
Voriconazolo | 0.25 |
Ambisome | 0.25 |

</div>
</div>

---

# Evoluzione

Poco dopo negativizzazione di emocolture:
- pallore cutaneo e mucoso, lesioni cutanee diffuse, discrete, non confluenti, interessanti tutto il soma, compresi volto, piante dei piedi e palmi, non pruriginose, edemi a carico degli AAII → verosimile disseminazione di infezione da Candida

Contemporaneamente:
- incremento ponderale (+ 11 kg), comparsa di edemi ingravescenti, epatosplenomegalia dolente → diagnosticata verosimile malattia veno-occlusiva epatica (VOD), secondaria a tossicità da PEG-asparaginasi

Trattamento potenziato con ambisome 5 (+1) mg/Kg ed associata anidulafungina
<!-- decreased susceptibility + not tested, suggested 5 mg/kg -->

---

# Interessamento d'organo

<div class="columns">
  <div>

  - Ecocardio TT: negativo
  - FOO: riscontro inizialmente di lesioni a sinistra, e poi bilateralmente
  - TC addome + RMN addome: rilevate "innumerevoli millimetriche aree ipointense dopo mdc in sede splenica ed epatica, alcune formazioni iperintense a livello della milza → lesioni compatibili con localizzazioni flogistico/ascessuali da Candida"

  </div>
  <video controls
      src="media/invasive_candidiasis_hepatosplenic.mp4"
      height=350px>
  </video>
  </div>
</div>

Trattatamento con Ambisome a vari dosaggi (da 3 a 10 mg/kg) in base al quadro clinico; associazione on/off di anidulafungina per localizzazioni metastatiche; infusioni intravitreali (1x dx, 2x sx).

Dimessa in regime di DH con ambisome 10 mg/kg (inefficaci dosaggi inferiori soprattutto per il quadro oculare).

---

# Definizione

- Candidiasis: broad term that refers to cutaneous, mucosal and deep-seated organ infections caused by fungi of the Candida genus
- Invasive candidiasis: bloodstream infections with Candida spp. (candidaemia) or deep-seated infection (regardless of candidemia)

- Chronic disseminated candidiasis (hepatosplenic candidiasis): deep infection that mainly involves the liver and spleen. Occurs mostly in patients after profound and prolonged neutropenia (e.g. acute haematological malignancies). Pathogenically definable as IRIS.

<!-- _footer: '[Rammaert, B., Desjardins, A. & Lortholary, O. New insights into hepatosplenic candidosis, a manifestation of chronic disseminated candidosis. Mycoses 55, e74–84 (2012)](http://dx.doi.org/10.1111/j.1439-0507.2012.02182.x)' -->

---

# Epidemiology

<div class="columns">
<div>

- *C. albicans* is the most common cause of candidemia; isolation of non-candida species is increasing (*C. glabrata*, *C. parapsilosis*, *C. tropicalis* ↔ *C. krusei*)
- *C. auris* is an emerging multidrug-resistant yeast capable of rapid spread in long-term acute care hospitals; it requires specialized methods for identification.
- Species differ in virulence: *C. parapsilosis* and *C. krusei* are less virulent than *C. albicans*, *C. tropicalis*, and *C. glabrata*.

</div>
<div>

Species | Italy | France | Spain |
-----|------|------|------|
C. albicans | 69.2% | 49% | 42.2% |
C. parapsilosis | 17% | 16.8% | 34.4% |
C. glabrata | 13% | 11% | 12.9% |
C. tropicalis | 5% | 14.1% | 4.7% |
C. krusei | 2% | 5.2% | 1.7% |
C. guillermondii | 1% | -- | -- |
C. kefir | -- | 9.9% | -- |

</div>
</div>

<!-- _footer: '[Chowdhary, A., Sharma, C. & Meis, J. F. PLoS Pathog. (2017)](http://dx.doi.org/10.1371/journal.ppat.1006290) ; [Kohlenberg, A., et al. & The Candida Auris Survey Collaborative Group. Euro Surveill. (2018)](http://dx.doi.org/10.2807/1560-7917.ES.2018.23.13.18-00136) ; [Pieralli, F. et al. Infection (2021)](http://dx.doi.org/10.1007/s15010-020-01535-z) ; [Lortholary, O. et al.  Intensive Care Med. (2017)](http://dx.doi.org/10.1007/s00134-017-4743-y) ; [Fortún, J. et al. J. Infect. (2012)](http://dx.doi.org/10.1016/j.jinf.2012.02.011) ; [Arendrup, M., Horn, T. & Frimodt-Møller, N. Infection (2002)](http://dx.doi.org/10.1007/s15010-002-2131-0)' -->

---

# Incidence

<div class="columns">
<div>

- around 3–5 per 100,000 persons in the general population and 1–2% of all medical and surgical ICU admissions
- higher incidence in hematological or neutropenic patients (up to 15-25 per 100,000 inpatient-days reported)
- hepatosplenic candidiasis: ranges from 3% to 29% in patients suffering from Acute Leukaemia
- ocular: ranges from 20% (older studies) to 2% (recent estimates), rarely vitreal involvement

</div>
</div>

---

# Risk factors for invasive disease

<div style="columns: 2">

- increased age, DM, colonization
- AKI ± dialysis
- trauma / burns
- CVC w/wo NPT; mechanical ventilation
- broad-spectrum antibiotic therapy and/or immunosuppressive therapy
- long-term hospital stay or ICU (especially with high APACHE score)
- surgery (particularly GI), GI perforation, anastomotic leaks

<br>

- immunosuppressed
  - hematological malignancies (tropicalis)
  - solid organ transplant or HSCT (krusei)
  - CHT (especially with mucositis)
  - neutropenia

</div>

---

# Pathogenesis

<div class="imgcols">

<div>

![height:400px](media/nature_pathogenesis.webp)
</div>

<div>
Normally commensal, detected on mucosal surfaces of ∼50–70% of healthy humans.

Portals of entry:

- GI mucosa
- vascular catheters
- infective nidus (e.g. pyelonephritis)
- TPN, unknown mechanism
- colonization, usually an intermediate step

</div>
</div>

<!-- _footer: '[Pappas, P. G., Lionakis, M. S., Arendrup, M. C., Ostrosky-Zeichner, L. & Kullberg, B. J. Invasive candidiasis. Nat Rev Dis Primers 4, 18026 (2018)](http://dx.doi.org/10.1038/nrdp.2018.26)' -->

---

# Clinica

- No clinical signs or symptoms are specific for invasive candidiasis
- should be suspected in patients with known risk factors who have an unexplained fever that is unresponsive to antibacterial treatment
- physical examination suggestive for invasive candidiasis may include eye lesions (chorioretinitis with or without vitritis) and skin lesions
  - lesions may appear suddenly as clusters of painless pustules (or maculae in neutropenic patients) on an erythematous base on any area of the body
- other symptomatology may be present depending on specific organs involved
  - for hepatosplenic candidiasis: abdominal upper quadrant pain, hepatosplenomegaly, nausea, anorexia

---

# Diagnostica

- emocolture: gold standard anche se negative in ~50% dei casi di IC disseminata e ~30% di IC con localizzazione d'organo
  - frequent sampling (once daily or more), larger volumes increase sensitivity

- biologia molecolare
  - BDG: alta sensibilità, bassa specificità per candida, alto valore predittivo negativo; consigliate almeno 2 determinazioni positive o in associazione a clinica o metodologia colturale positiva
  - Candida mannan antigen + antimannan antibodies: mostly used for BCx-negative hepatosplenic candidiasis and CNS candidiasis.
  - DNA-based: alta sensibilità e specificità, rapida positivizzazione; non validati

<!-- _footer: '[Berenguer, J. et al. Microbiol. Infect. Dis. (1993)](http://dx.doi.org/10.1016/0732-8893(93)90020-8) ; [Mikulska, M. et al. Crit. Care 14, R222 (2010)](http://dx.doi.org/10.1186/cc9365) ; [Arendrup, M. C. et al. J. Clin. Microbiol. (2011)](http://dx.doi.org/10.1128/JCM.00179-11)' -->

---

# Management

Il focus è la ricerca di foci infettivi metastatici.

- valutazione oftalmologica con FOO: consigliata di routine; come tempistica consigliata esecuzione nella prima settimana dopo risoluzione della neutrofilia
- ecocardiografia: in particolare se emocolture persistentemente positive (> 96h)
  - alcuni articoli sembrano suggerire che un'ecocardio di routine non sia necessario vista la bassa incidenza (~6%)
  - C. albicans e C. parapsilosis sembrano essere le principali responsabili
  - nei pazienti neutropenici è una complicanza rara

<!-- _footer: '[Scudeller, L. et al. An Italian consensus for invasive candidiasis management (ITALIC). Infection (2014)](http://dx.doi.org/10.1007/s15010-013-0558-0) <br>
[Fernández-Cruz, A. et al. The search for endocarditis in patients with candidemia: a systematic recommendation for echocardiography? A prospective cohort. Eur. J. Clin. Microbiol. Infect. Dis. 34, 1543–1549 (2015)](http://dx.doi.org/10.1007/s10096-015-2384-z)' -->

---

# Management (continued)

- emocolture ogni 24/48h consigliate fino a due campioni negativi consecutivi
- imaging addominale: ascessi epato-splenici sono poco comuni ma da sospettare in pazienti con sintomi addominali, alterazioni della funzionalità epatica o febbre persistente
  - esame di scelta: TC addome con mdc
- in neutropenic patients, sources of candidiasis other than a CVC may be relevant (e.g. GI mucosa)
  - diverging data on CVC removal; interestingly a study assessing early CVC removal effect on mortality showed no clinical benefit

<!-- _footer: '[Nucci, M. et al. Early removal of central venous catheter in patients with candidemia does not improve outcome: analysis of 842 patients from 2 randomized clinical trials. Clin. Infect. Dis. 51, 295–303 (2010)](http://dx.doi.org/10.1086/653935)' -->

---

# Treatment

<div class="imgcols">

<div>

![](media/nature_treatment.webp)

</div>

<div>

- requisiti consigliati per step-down therapy: paziente stabile, isolato suscettibile, emocolture negative (in caso di fluconazolo consigliato anche la non precedente esposizione ad azoli)
- voriconazolo può essere usato per ampliare lo spettro a coprire le muffe
- resistenza a fluconazolo in aumento, specialmente in *C. glabrata*; intrinseca per *C. krusei*

</div>
</div>

<!-- _footer: '[Pappas, P. G., Lionakis, M. S., Arendrup, M. C., Ostrosky-Zeichner, L. & Kullberg, B. J. Invasive candidiasis. Nat Rev Dis Primers 4, 18026 (2018)](http://dx.doi.org/10.1038/nrdp.2018.26)' -->

---

# Treatment

- delay (even 1 day) in initiation of effective antifungal therapy has been associated with a doubling of mortality
- azoli diversi da fluconazolo e voriconazolo generalmente non raccomandati, così come AmB non liposomiale
- G-CSF può essere indicato in caso di persistente candidemia se si prevede neutropenia prolungata
- macular involvement w/wo vitreal involvement: CONSIDER intravitreal injections of either AmB or voriconazole

Inoltre per la forma epatosplenica:
- steroid can be associated (short course - 1-2 weeks) in case of persistent fever

<!-- _footer: '[Pappas, P. G. et al. Clinical Practice Guideline for the Management of Candidiasis: 2016 Update by the Infectious Diseases Society of America. Clin. Infect. Dis. (2016)](http://dx.doi.org/10.1093/cid/civ933) <br>
[Garey, K. W. et al. Time to initiation of fluconazole therapy impacts mortality in patients with candidemia: a multi-institutional study. Clin. Infect. Dis. 43, 25–31 (2006)](http://dx.doi.org/10.1086/504810)' -->

---

# Duration of therapy

The optimal duration of therapy for candidemia is uncertain.

- candidemia in the absence of metastatic complications: a minimum of two weeks of therapy after blood cultures become negative
  - resolution of symptoms attributable to candidemia and resolution of neutropenia prior to discontinuation of antifungal therapy
- candidemia and metastatic foci of infection:
  - endophtalmitis: until all active eye lesions have resolved
  - disseminated / chronic disseminated (hepatosplenic): fwup with imaging every two to three months; therapy should be continued until resolution of the lesions on imaging

<!-- _footer: '[Pappas, P. G. et al. Clinical Practice Guideline for the Management of Candidiasis: 2016 Update by the Infectious Diseases Society of America. Clin. Infect. Dis. (2016)](http://dx.doi.org/10.1093/cid/civ933)' -->