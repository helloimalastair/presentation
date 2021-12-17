---
marp: true
# theme: gaia
author: Daniele Riccucci
paginate: true
# cannot use bg in syntax here
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
      grid-template-columns: 1fr 1fr;
      grid-gap: 1em;
      box-sizing: border-box;
      background-color: inherit;
      color: inherit;
      width: 100%;
      height: 100%;
      align-items: center;
      justify-content: center;
    }
---
<!--
_class:
  - lead
  - invert
-->

# Fusariosis

---
# Intro
Paziente di 35 anni

Diagnosi di Leucemia Mieloide acuta in Maggio 2020 esordita con febbre, tosse, iperleucocitosi, blastosi periferica, anemia severa e lieve piastrinopenia.

Trattato con cicli di doxorubicina + ARA-C in prima linea, poi terapia sperimentale con uproleselan + fludarabina + ARA-C + idarubicina.

- Sierologia rilevante all'ingresso: HBcAb pos, HBV-DNA neg

---
# Caso clinico

Durante la fase di neutropenia comparsa di:
- febbre persistente
- sinusite con area eritemato-edematosa dolente a livello della radice dell'ala del naso a destra, estesa all'angolo mediale dell'occhio omolaterale

Da fine maggio multiple valutazioni per la stessa sintomatologia.
Diagnostica:
- PCT negativa, GM negativo, BDG neg
- colturale di secreto nasale: negativa ricerca di lieviti, sviluppo di flora saprofitica
- TC seni paranasali + RM orbite: flogosi cronica dei seni paranasali con concrezioni calcifiche; non coinvolgimento orbitario

Inizialmente trattato empiricamente con: Ambisome ∧ meropenem ∧ vancomicina.

---

# Evoluzione

- severa neutropenia; BDG 4 > 9 > 16 > 27; GM neg; PCT neg
- emocolture (multipli set da CVC e periferico) pos per *Fusarium Solani complex*
- comparsa di lesioni cutanee al cuoio capelluto, radice del collo, braccio sinistro e pollice dx
- TC seni paranasali: aumento dell'impegno flogistico; comparsa di bolle gassose nei tessuti molli paraorbitari; irregolarità ed aspetto discontinuo del profilo dell'osso mascellare e del seno mascellare di destra e successivamente soluzione di continuo a livello della corticale; osteolisi dell'arcata dentale superiore.
- HRCT torace: numerose aree consolidative pseudonodulari ed addensamenti GG (DDx con PCP)
- supporto respiratorio anche con CPAP

---
# Imaging

<div style="
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr;
  grid-gap: 1%;
  box-sizing: border-box;
  background-color: inherit;
  color: inherit;
  width: 100%;
  height: 100%;
  align-items: center;
  justify-content: center;">
  <div>
  <video controls
      src="media/fusariosis_2021-06-27.mp4"
      width="100%">
  </video>
  </div><div>
  <video controls
      src="media/fusariosis_2021-07-06.mp4"
      width="100%">
  </video>
  </div><div>
  <video controls
      src="media/fusariosis_2021-07-14.mp4"
      width="100%">
  </video>
  </div>
</div>

---

# Evoluzione (continua)

- meatomia mascellare: ife fungine (in DDx con *Aspergillus*)
- oculistica: corioretinite al FOO; peggioramento del visus, edema periorbitario a destra, con eritema della regione sotto oculare e zigomatica
- ecocardio: negativo
- TC encefalo: negativa
- FBS + BAL non eseguibile

---

# Gestione

- Multipli cicli di terapia antibiotica, incluso bactrim per PCP
- associazione periodica di voriconazolo (in concomitanza dei peggioramenti clinici) anche se MIC sfavorevole (4) e modifiche della posologia di Ambisome
- trattamento endovitreale con Ambisome, complicato da ematoma ed ascesso del vitreo
- vitrectomia + esame colturale: negativo
- intervento di bonifica (oculistico + ORL): enucleazione occhio destro, toelette delle croste nasali, bonifica di necrosi settica della cartilagine quadrangolare e spina nasale anteriore, 1/3 anteriore del turbinato inferiore, parete mascellare mediale, dotto nasolacrimale; maxillectomia mediale tipo I con uncinectomia completa; etmoidectomia

---

# Conclusione

- ematologicamente remissione di malattia, candidato a MUD (Matched Unrelated Donor)
- dimesso a domicilio con prosecuzione di AmB 5 mg/Kg fino a 6 settimane dall' intervento di bonifica, poi valutazione per profilassi
- oculistica: quadro stabile, da rivalutare mensilmente
- ORL: quadro stabile post intervento

---

# Epidemiology

Fusarium is a mould classified as hyalohyphomycosis, defined by the presence of hyaline hyphae in tissues.
Widely distributed in soil and water worldwide. At least 7 species complexes comprising multiple species have been reported to cause significant human disease (in order of frequency):
- Fusarium solani species complex (FSSC) (~50%)
- Fusarium oxysporum species complex (FOSC)
- Fusarium fujikuroi species complex (FFSC)
- Others: Fusarium incarnatum-equiseti species complex, Fusarium chlamidosporum species complex, Fusarium dimerum species complex, Fusarium sporotrichoides species complex

<!-- _footer: '[van Diepeningen, A. D., Al-Hatmi, A. M. S., Brankovics, B. & de Hoog, G. S. Taxonomy and Clinical Spectra of Fusarium Species ... Current Clinical Microbiology Reports (2014)](https://doi.org/10.1007/s40588-014-0003-x) <br> [Balajee, S. A. et al. Sequence-based identification of Aspergillus, fusarium, and mucorales species in the clinical mycology laboratory ... J. Clin. Microbiol. (2009)](http://dx.doi.org/10.1128/JCM.01685-08)' -->

---

# Incidence

<div class="columns">
<div>

![height:400px](media/incidenza_emato.webp)

</div>
<div>

![height:400px](media/incidenza_HSCT.webp)

</div>
</div>

<!-- _footer: '[Pagano, L. et al. The epidemiology of fungal infections in patients with hematologic malignancies: the SEIFEM-2004 study. Haematologica 91, 1068–1075 (2006)](https://www.ncbi.nlm.nih.gov/pubmed/16885047) <br>
[Pagano, L. et al. Fungal infections in recipients of hematopoietic stem cell transplants: results of the SEIFEM B-2004 study--Sorveglianza Epidemiologica Infezioni Fungine Nelle Emopatie Maligne. Clin. Infect. Dis. 45, 1161–1170 (2007)](http://dx.doi.org/10.1086/522189)' -->

---

# Pathogenesis

- entry: airborne, direct inoculation (also self-inoculation, e.g.  onychomycosis or intertrigo), CVC and central catheters
- risk factors - immunocompromised patients (neutropenia or severe T-cell immunodeficiency), Ibrutinib
- F. solani is thought to be the most virulent Fusarium species

<!-- _footer: '[Nelson, P. E., Dignani, M. C. & Anaissie, E. J. Taxonomy, biology, and clinical aspects of Fusarium species. Clin. Microbiol. Rev. 7, 479–504 (1994)](http://dx.doi.org/10.1128/CMR.7.4.479)<br>[Mayayo, E., Pujol, I. & Guarro, J. Experimental pathogenicity of four opportunist Fusarium species in a murine model. J. Med. Microbiol. 48, 363–366 (1999)](http://dx.doi.org/10.1099/00222615-48-4-363)' -->

---

# Clinical disease spectrum

- Immunocompetent
  - common: keratitis (contact lenses especially), onychomycosis
  - uncommon: cutaneous (burns, wounds), peritonitis (patients receiving CAPD), endocarditis, pneumonia, sinusitis, endophthalmitis, thrombophlebitis, fungemia, arthritis
- Immunocompromised
  - disseminated: multiorgan infection, isolated fungemia
  - localized
    - common: cellulitis, sinusitis, pneumonia
    - uncommon: CNS infection, endophtalmitis, arthritis/osteomyelitis

<!-- _footer: '[Nucci, M. & Anaissie, E. Cutaneous infection by Fusarium species in healthy and immunocompromised hosts: implications for diagnosis and management. Clin. Infect. Dis. 35, 909–920 (2002)](http://dx.doi.org/10.1086/342328) <br>
[Nucci, M. & Anaissie, E. Fusarium infections in immunocompromised patients. Clin. Microbiol. Rev. (2007)](https://doi.org/10.1128/cmr.00014-07)' -->
---
# Immunocompetent host

- keratitis: typically more indolent than bacterial keratitis; nonspecific
- onychomycosis: nonspecific
- interdigital intertrigo, tinea pedis, hyperkeratotic plantar lesions; nonspecific
- deep cutaneous infections: usually localized and associated to trauma, burns
- others: all are nonspecific and include cellulitis, ulcers, abscesses, chronic sinusitis, pneumonia, endophthalmitis, osteomyelitis, septic arthritis, brain abscess, cystitis, and peritonitis.

---

# Immunocompromised host

- disseminated disease (~70%): persistent fever (>10 days) non-responsive to antibacterial and antifungal therapy in neutropenic (<100 cells/mm3) patients; high mortality (~60-80%)
- pneumonia: commonly associated with invasive disease (~50%); nonspecific; radiographic features may include nodules with halo sign and cavitary lesions
- sinusitis: may be associated with fusarial pneumonia; indistinguishable from Aspergillus; necrosis of the mucosa is characteristic due to vascular invasion
- cutaneous lesions: localized (usually cellulitis) or disseminated (painful erythematous papulae or nodules with central necrosis; DDx ecthyma gangrenosum)

A 21% improvement in survival has been reported due to the use of liposomial AmB and voriconazole (despite unfavorable MICs)

<!-- _footer: '[Nucci, M. & Anaissie, E. Fusarium infections in immunocompromised patients. Clin. Microbiol. Rev. 20, 695–704 (2007)](http://dx.doi.org/10.1128/CMR.00014-07) <br>
[Nucci, F., Nouér, S. A., Capone, D., Anaissie, E. & Nucci, M. Fusariosis. Semin. Respir. Crit. Care Med. 36, 706–714 (2015)](http://dx.doi.org/10.1055/s-0035-1562897) <br>
[Nucci, M. et al. Improvement in the outcome of invasive fusariosis in the last decade. Clin. Microbiol. Infect. 20, 580–585 (2014)](http://dx.doi.org/10.1111/1469-0691.12409)' -->

---

# Diagnosis

- direct microscopy of various materials (e.g. nail scrapings, corneal scrapings, skin biopsy, sinus aspirates, respiratory secretions, blood cultures): essential investigation
- histopathology: essential, but DDx with Aspergillus and other hyalohyphomycoses
- culture (of various material): essential investigation; blood cultures frequently (~40%) positive compared to other invasive molds
- pan-fungal PCR: high negative predictive value; Fusarium-specific PCR available in some labs
- β 1,3-D-glucan test: usually positive, not specific
- depending on clinical signs and symptoms and in hematological patients: HRCT thorax + sinuses

<!-- _footer: '[Tortorano, A. M. et al. ESCMID and ECMM joint guidelines on diagnosis and management of hyalohyphomycosis: Fusarium spp., Scedosporium spp. and others. Clin. Microbiol. Infect. (2014)](http://dx.doi.org/10.1111/1469-0691.12465) <br> [Liu, K., Howell, D. N., Perfect, J. R. & Schell, W. A. Morphologic criteria for the preliminary identification of Fusarium, Paecilomyces, and Acremonium species by histopathology. Am. J. Clin. Pathol. (1998)](http://dx.doi.org/10.1093/ajcp/109.1.45)' -->

---

# Treatment

First line (can be associated):
- Amphotericin B liposomial or lipid complex (3-5 mg/kg, up to 10 mg/kg); most effective on Italian isolates
- voriconazole (6 mg/kg x2 + 4 mg/kg)

Salvage treatment:
- posaconazole: success rate ~ 50%
- voriconazole: as above

Often highly resistant to various compounds; intrinsically resistant to echinocandins

<!-- _footer: '[Tortorano, A. M. et al. Species distribution and in vitro antifungal susceptibility patterns of 75 clinical isolates of Fusarium spp. from northern Italy. Antimicrob. Agents Chemother. (2008)](http://dx.doi.org/10.1128/AAC.00272-08) <br>
[Tortorano, A. M. et al. ESCMID and ECMM joint guidelines on diagnosis and management of hyalohyphomycosis: Fusarium spp., Scedosporium spp. and others. Clin. Microbiol. Infect. (2014)](http://dx.doi.org/10.1111/1469-0691.12465) <br>
[McCarthy, M. W., Katragkou, A., Iosifidis, E., Roilides, E. & Walsh, T. J. Recent Advances in the Treatment of Scedosporiosis and Fusariosis. J Fungi (Basel) 4, (2018)](http://dx.doi.org/10.3390/jof4020073) <br>
[Al-Hatmi, A. M. S. et al. Current antifungal treatment of fusariosis. Int. J. Antimicrob. Agents 51, 326–332 (2018)](http://dx.doi.org/10.1016/j.ijantimicag.2017.06.017)' -->

---

# Treatment (continues)

Duration: generally until all signs and symptoms of the infection have resolved, radiographic abnormalities have stabilized, and significant immune reconstitution has occurred

Additional treatment:
- surgical debridement of infected tissues
- removal of venous catheters in confirmed catheter-related fusariosis
- reversal of the immunocompromised state

<!-- _footer: '[Tortorano, A. M. et al. ESCMID and ECMM joint guidelines on diagnosis and management of hyalohyphomycosis: Fusarium spp., Scedosporium spp. and others. Clin. Microbiol. Infect. (2014)](http://dx.doi.org/10.1111/1469-0691.12465)' -->

---

# Prophylaxis
## Primary

- Avoidance of skin breakdown
- examination for and treatment of onychomycosis, interdigital intertrigo, and paronychia and surgical debridement of infected wounds prior to neutropenia
- high-efficiency particulate air filter and positive pressure isolation rooms,avoid tap water during neutropenia
- culture of suspicious cutaneous lesion (especially interdigital intertrigo or onychomycosis) followed by rimary prophylaxis with voriconazole or posaconazole if positive

<!-- _footer: '[Fernández-Cruz, A. et al. A retrospective cohort of invasive fusariosis in the era of antimould prophylaxis. Med. Mycol. 58, 300–309 (2020)](http://dx.doi.org/10.1093/mmy/myz060) <br>
[Varon, A. G. et al. Antimold Prophylaxis May Reduce the Risk of Invasive Fusariosis in Hematologic Patients with Superficial Skin Lesions with Positive Culture for Fusarium. Antimicrob. Agents Chemother. 60, 7290–7294 (2016)](http://dx.doi.org/10.1128/AAC.00636-16)' -->

---
# Prophylaxis
## Secondary

During periods of increased immunosuppression if previous infection
- blood cultures ± CT to evaluate for infectious foci prior immunosuppressive therapies/procedures
- voriconazole, posaconazole, or a lipid formulation of amphotericin B
- G-CSF plus dexamethasone-elicited granulocyte transfusions during periods of expected neutropenia

<!-- _footer: '[Nucci, M. et al. Outcomes of patients with invasive fusariosis who undergo further immunosuppressive treatments, is there a role for secondary prophylaxis? Mycoses 62, 413–417 (2019)](http://dx.doi.org/10.1111/myc.12901)' -->---
marp: true
# theme: gaia
author: Daniele Riccucci
paginate: true
# cannot use bg in syntax here
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
      grid-template-columns: 1fr 1fr;
      grid-gap: 1em;
      box-sizing: border-box;
      background-color: inherit;
      color: inherit;
      width: 100%;
      height: 100%;
      align-items: center;
      justify-content: center;
    }
---
<!--
_class:
  - lead
  - invert
-->

# Fusariosis

---
# Intro
Paziente di 35 anni

Diagnosi di Leucemia Mieloide acuta in Maggio 2020 esordita con febbre, tosse, iperleucocitosi, blastosi periferica, anemia severa e lieve piastrinopenia.

Trattato con cicli di doxorubicina + ARA-C in prima linea, poi terapia sperimentale con uproleselan + fludarabina + ARA-C + idarubicina.

- Sierologia rilevante all'ingresso: HBcAb pos, HBV-DNA neg

---
# Caso clinico

Durante la fase di neutropenia comparsa di:
- febbre persistente
- sinusite con area eritemato-edematosa dolente a livello della radice dell'ala del naso a destra, estesa all'angolo mediale dell'occhio omolaterale

Da fine maggio multiple valutazioni per la stessa sintomatologia.
Diagnostica:
- PCT negativa, GM negativo, BDG neg
- colturale di secreto nasale: negativa ricerca di lieviti, sviluppo di flora saprofitica
- TC seni paranasali + RM orbite: flogosi cronica dei seni paranasali con concrezioni calcifiche; non coinvolgimento orbitario

Inizialmente trattato empiricamente con: Ambisome ∧ meropenem ∧ vancomicina.

---

# Evoluzione

- severa neutropenia; BDG 4 > 9 > 16 > 27; GM neg; PCT neg
- emocolture (multipli set da CVC e periferico) pos per *Fusarium Solani complex*
- comparsa di lesioni cutanee al cuoio capelluto, radice del collo, braccio sinistro e pollice dx
- TC seni paranasali: aumento dell'impegno flogistico; comparsa di bolle gassose nei tessuti molli paraorbitari; irregolarità ed aspetto discontinuo del profilo dell'osso mascellare e del seno mascellare di destra e successivamente soluzione di continuo a livello della corticale; osteolisi dell'arcata dentale superiore.
- HRCT torace: numerose aree consolidative pseudonodulari ed addensamenti GG (DDx con PCP)
- supporto respiratorio anche con CPAP

---
# Imaging

<div style="
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr;
  grid-gap: 1%;
  box-sizing: border-box;
  background-color: inherit;
  color: inherit;
  width: 100%;
  height: 100%;
  align-items: center;
  justify-content: center;">
  <div>
  <video controls
      src="media/fusariosis_2021-06-27.mp4"
      width="100%">
  </video>
  </div><div>
  <video controls
      src="media/fusariosis_2021-07-06.mp4"
      width="100%">
  </video>
  </div><div>
  <video controls
      src="media/fusariosis_2021-07-14.mp4"
      width="100%">
  </video>
  </div>
</div>

---

# Evoluzione (continua)

- meatomia mascellare: ife fungine (in DDx con *Aspergillus*)
- oculistica: corioretinite al FOO; peggioramento del visus, edema periorbitario a destra, con eritema della regione sotto oculare e zigomatica
- ecocardio: negativo
- TC encefalo: negativa
- FBS + BAL non eseguibile

---

# Gestione

- Multipli cicli di terapia antibiotica, incluso bactrim per PCP
- associazione periodica di voriconazolo (in concomitanza dei peggioramenti clinici) anche se MIC sfavorevole (4) e modifiche della posologia di Ambisome
- trattamento endovitreale con Ambisome, complicato da ematoma ed ascesso del vitreo
- vitrectomia + esame colturale: negativo
- intervento di bonifica (oculistico + ORL): enucleazione occhio destro, toelette delle croste nasali, bonifica di necrosi settica della cartilagine quadrangolare e spina nasale anteriore, 1/3 anteriore del turbinato inferiore, parete mascellare mediale, dotto nasolacrimale; maxillectomia mediale tipo I con uncinectomia completa; etmoidectomia

---

# Conclusione

- ematologicamente remissione di malattia, candidato a MUD (Matched Unrelated Donor)
- dimesso a domicilio con prosecuzione di AmB 5 mg/Kg fino a 6 settimane dall' intervento di bonifica, poi valutazione per profilassi
- oculistica: quadro stabile, da rivalutare mensilmente
- ORL: quadro stabile post intervento

---

# Epidemiology

Fusarium is a mould classified as hyalohyphomycosis, defined by the presence of hyaline hyphae in tissues.
Widely distributed in soil and water worldwide. At least 7 species complexes comprising multiple species have been reported to cause significant human disease (in order of frequency):
- Fusarium solani species complex (FSSC) (~50%)
- Fusarium oxysporum species complex (FOSC)
- Fusarium fujikuroi species complex (FFSC)
- Others: Fusarium incarnatum-equiseti species complex, Fusarium chlamidosporum species complex, Fusarium dimerum species complex, Fusarium sporotrichoides species complex

<!-- _footer: '[van Diepeningen, A. D., Al-Hatmi, A. M. S., Brankovics, B. & de Hoog, G. S. Taxonomy and Clinical Spectra of Fusarium Species ... Current Clinical Microbiology Reports (2014)](https://doi.org/10.1007/s40588-014-0003-x) <br> [Balajee, S. A. et al. Sequence-based identification of Aspergillus, fusarium, and mucorales species in the clinical mycology laboratory ... J. Clin. Microbiol. (2009)](http://dx.doi.org/10.1128/JCM.01685-08)' -->

---

# Incidence

<div class="columns">
<div>

![height:400px](media/incidenza_emato.webp)

</div>
<div>

![height:400px](media/incidenza_HSCT.webp)

</div>
</div>

<!-- _footer: '[Pagano, L. et al. The epidemiology of fungal infections in patients with hematologic malignancies: the SEIFEM-2004 study. Haematologica 91, 1068–1075 (2006)](https://www.ncbi.nlm.nih.gov/pubmed/16885047) <br>
[Pagano, L. et al. Fungal infections in recipients of hematopoietic stem cell transplants: results of the SEIFEM B-2004 study--Sorveglianza Epidemiologica Infezioni Fungine Nelle Emopatie Maligne. Clin. Infect. Dis. 45, 1161–1170 (2007)](http://dx.doi.org/10.1086/522189)' -->

---

# Pathogenesis

- entry: airborne, direct inoculation (also self-inoculation, e.g.  onychomycosis or intertrigo), CVC and central catheters
- risk factors - immunocompromised patients (neutropenia or severe T-cell immunodeficiency), Ibrutinib
- F. solani is thought to be the most virulent Fusarium species

<!-- _footer: '[Nelson, P. E., Dignani, M. C. & Anaissie, E. J. Taxonomy, biology, and clinical aspects of Fusarium species. Clin. Microbiol. Rev. 7, 479–504 (1994)](http://dx.doi.org/10.1128/CMR.7.4.479)<br>[Mayayo, E., Pujol, I. & Guarro, J. Experimental pathogenicity of four opportunist Fusarium species in a murine model. J. Med. Microbiol. 48, 363–366 (1999)](http://dx.doi.org/10.1099/00222615-48-4-363)' -->

---

# Clinical disease spectrum

- Immunocompetent
  - common: keratitis (contact lenses especially), onychomycosis
  - uncommon: cutaneous (burns, wounds), peritonitis (patients receiving CAPD), endocarditis, pneumonia, sinusitis, endophthalmitis, thrombophlebitis, fungemia, arthritis
- Immunocompromised
  - disseminated: multiorgan infection, isolated fungemia
  - localized
    - common: cellulitis, sinusitis, pneumonia
    - uncommon: CNS infection, endophtalmitis, arthritis/osteomyelitis

<!-- _footer: '[Nucci, M. & Anaissie, E. Cutaneous infection by Fusarium species in healthy and immunocompromised hosts: implications for diagnosis and management. Clin. Infect. Dis. 35, 909–920 (2002)](http://dx.doi.org/10.1086/342328) <br>
[Nucci, M. & Anaissie, E. Fusarium infections in immunocompromised patients. Clin. Microbiol. Rev. (2007)](https://doi.org/10.1128/cmr.00014-07)' -->
---
# Immunocompetent host

- keratitis: typically more indolent than bacterial keratitis; nonspecific
- onychomycosis: nonspecific
- interdigital intertrigo, tinea pedis, hyperkeratotic plantar lesions; nonspecific
- deep cutaneous infections: usually localized and associated to trauma, burns
- others: all are nonspecific and include cellulitis, ulcers, abscesses, chronic sinusitis, pneumonia, endophthalmitis, osteomyelitis, septic arthritis, brain abscess, cystitis, and peritonitis.

---

# Immunocompromised host

- disseminated disease (~70%): persistent fever (>10 days) non-responsive to antibacterial and antifungal therapy in neutropenic (<100 cells/mm3) patients; high mortality (~60-80%)
- pneumonia: commonly associated with invasive disease (~50%); nonspecific; radiographic features may include nodules with halo sign and cavitary lesions
- sinusitis: may be associated with fusarial pneumonia; indistinguishable from Aspergillus; necrosis of the mucosa is characteristic due to vascular invasion
- cutaneous lesions: localized (usually cellulitis) or disseminated (painful erythematous papulae or nodules with central necrosis; DDx ecthyma gangrenosum)

A 21% improvement in survival has been reported due to the use of liposomial AmB and voriconazole (despite unfavorable MICs)

<!-- _footer: '[Nucci, M. & Anaissie, E. Fusarium infections in immunocompromised patients. Clin. Microbiol. Rev. 20, 695–704 (2007)](http://dx.doi.org/10.1128/CMR.00014-07) <br>
[Nucci, F., Nouér, S. A., Capone, D., Anaissie, E. & Nucci, M. Fusariosis. Semin. Respir. Crit. Care Med. 36, 706–714 (2015)](http://dx.doi.org/10.1055/s-0035-1562897) <br>
[Nucci, M. et al. Improvement in the outcome of invasive fusariosis in the last decade. Clin. Microbiol. Infect. 20, 580–585 (2014)](http://dx.doi.org/10.1111/1469-0691.12409)' -->

---

# Diagnosis

- direct microscopy of various materials (e.g. nail scrapings, corneal scrapings, skin biopsy, sinus aspirates, respiratory secretions, blood cultures): essential investigation
- histopathology: essential, but DDx with Aspergillus and other hyalohyphomycoses
- culture (of various material): essential investigation; blood cultures frequently (~40%) positive compared to other invasive molds
- pan-fungal PCR: high negative predictive value; Fusarium-specific PCR available in some labs
- β 1,3-D-glucan test: usually positive, not specific
- depending on clinical signs and symptoms and in hematological patients: HRCT thorax + sinuses

<!-- _footer: '[Tortorano, A. M. et al. ESCMID and ECMM joint guidelines on diagnosis and management of hyalohyphomycosis: Fusarium spp., Scedosporium spp. and others. Clin. Microbiol. Infect. (2014)](http://dx.doi.org/10.1111/1469-0691.12465) <br> [Liu, K., Howell, D. N., Perfect, J. R. & Schell, W. A. Morphologic criteria for the preliminary identification of Fusarium, Paecilomyces, and Acremonium species by histopathology. Am. J. Clin. Pathol. (1998)](http://dx.doi.org/10.1093/ajcp/109.1.45)' -->

---

# Treatment

First line (can be associated):
- Amphotericin B liposomial or lipid complex (3-5 mg/kg, up to 10 mg/kg); most effective on Italian isolates
- voriconazole (6 mg/kg x2 + 4 mg/kg)

Salvage treatment:
- posaconazole: success rate ~ 50%
- voriconazole: as above

Often highly resistant to various compounds; intrinsically resistant to echinocandins

<!-- _footer: '[Tortorano, A. M. et al. Species distribution and in vitro antifungal susceptibility patterns of 75 clinical isolates of Fusarium spp. from northern Italy. Antimicrob. Agents Chemother. (2008)](http://dx.doi.org/10.1128/AAC.00272-08) <br>
[Tortorano, A. M. et al. ESCMID and ECMM joint guidelines on diagnosis and management of hyalohyphomycosis: Fusarium spp., Scedosporium spp. and others. Clin. Microbiol. Infect. (2014)](http://dx.doi.org/10.1111/1469-0691.12465) <br>
[McCarthy, M. W., Katragkou, A., Iosifidis, E., Roilides, E. & Walsh, T. J. Recent Advances in the Treatment of Scedosporiosis and Fusariosis. J Fungi (Basel) 4, (2018)](http://dx.doi.org/10.3390/jof4020073) <br>
[Al-Hatmi, A. M. S. et al. Current antifungal treatment of fusariosis. Int. J. Antimicrob. Agents 51, 326–332 (2018)](http://dx.doi.org/10.1016/j.ijantimicag.2017.06.017)' -->

---

# Treatment (continues)

Duration: generally until all signs and symptoms of the infection have resolved, radiographic abnormalities have stabilized, and significant immune reconstitution has occurred

Additional treatment:
- surgical debridement of infected tissues
- removal of venous catheters in confirmed catheter-related fusariosis
- reversal of the immunocompromised state

<!-- _footer: '[Tortorano, A. M. et al. ESCMID and ECMM joint guidelines on diagnosis and management of hyalohyphomycosis: Fusarium spp., Scedosporium spp. and others. Clin. Microbiol. Infect. (2014)](http://dx.doi.org/10.1111/1469-0691.12465)' -->

---

# Prophylaxis
## Primary

- Avoidance of skin breakdown
- examination for and treatment of onychomycosis, interdigital intertrigo, and paronychia and surgical debridement of infected wounds prior to neutropenia
- high-efficiency particulate air filter and positive pressure isolation rooms,avoid tap water during neutropenia
- culture of suspicious cutaneous lesion (especially interdigital intertrigo or onychomycosis) followed by rimary prophylaxis with voriconazole or posaconazole if positive

<!-- _footer: '[Fernández-Cruz, A. et al. A retrospective cohort of invasive fusariosis in the era of antimould prophylaxis. Med. Mycol. 58, 300–309 (2020)](http://dx.doi.org/10.1093/mmy/myz060) <br>
[Varon, A. G. et al. Antimold Prophylaxis May Reduce the Risk of Invasive Fusariosis in Hematologic Patients with Superficial Skin Lesions with Positive Culture for Fusarium. Antimicrob. Agents Chemother. 60, 7290–7294 (2016)](http://dx.doi.org/10.1128/AAC.00636-16)' -->

---
# Prophylaxis
## Secondary

During periods of increased immunosuppression if previous infection
- blood cultures ± CT to evaluate for infectious foci prior immunosuppressive therapies/procedures
- voriconazole, posaconazole, or a lipid formulation of amphotericin B
- G-CSF plus dexamethasone-elicited granulocyte transfusions during periods of expected neutropenia

<!-- _footer: '[Nucci, M. et al. Outcomes of patients with invasive fusariosis who undergo further immunosuppressive treatments, is there a role for secondary prophylaxis? Mycoses 62, 413–417 (2019)](http://dx.doi.org/10.1111/myc.12901)' -->