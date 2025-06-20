## Data Description

### File Formats
- **`.mat` files**: Contain raw EEG signals from the four channels (F3, F4, Fz, Cz).
- **`.txt` files**: Include expert-annotated sleep staging labels (each mark corresponds to 3 seconds of recording).

### Sleep Stage Codes
| Code  | Description               |
|-------|---------------------------|
| WN    | Wake with Noise           |
| Wake  | Wakefulness               |
| SOMN  | Sleep Onset with Noise    |
| REM   | Rapid Eye Movement        |
| REMN  | REM with Noise            |
| NREM  | Non-REM Sleep             |
| NREMN | Non-REM Sleep with Noise  |

### Technical Specifications
- **Sampling frequency (sf)**: 400 Hz
- **Time resolution**: 3-second epochs (matching annotation intervals)

---

## Population  

### Study Participants  
Twelve young, healthy domestic dogs (mean age: **64.4 ± [SD]** months; mean weight: **20.08 ± 9.1 kg**), representing a mix of breeds and sexes, participated in this study. All animals underwent three stages on separate days:  
1. **Acclimatization**  
2. **Recording with trazodone**  
3. **Recording without trazodone**  

### Ethical Approval  
All procedures were approved by the **Institutional Animal Care and Use Committee (IACUC)** at North Carolina State University (NCSU; protocol number `21-303`). The dogs were client-owned and served as age controls in an ongoing longitudinal study on neuro-aging at the NCSU College of Veterinary Medicine ([Fefer et al., 2022](#references); [Panek et al., 2020](#references)).  

**Informed consent** was obtained from all owners prior to participation.  

---

### Table 1: Participant Demographics  
| Dog | Breed             | Sex  | Weight (kg) | Age (months) |  
|-----|-------------------|------|-------------|--------------|  
| 1   | Maltese           | F    | 5.4         | 79.6         |  
| 2   | Labrador Retriever| FS   | 27.1        | 103.8        |  
| 3   | Pitbull           | FS   | 23.1        | 36.1         |  
| 4   | Pitbull mix       | MC   | 30.6        | 45.2         |  
| 5   | Lab mix           | FS   | 21.4        | 57.5         |  
| 6   | Pitbull mix       | MC   | 22.2        | 60.4         |  
| 7   | Mix breed         | FS   | 21.2        | 35.7         |  
| 8   | Labrador Retriever| MC   | 31.5        | 46.0         |  
| 9   | Beagle            | MC   | 7.5         | 15.7         |  
| 10  | Shitzu            | MC   | 6.2         | 83.2         |  
| 11  | Pitbull           | MC   | 30.3        | 48.0         |  
| 12  | Mix breed         | MC   | 14.5        | 152.0        |  

**Sex codes**: F = Female, M = Male, FS = Female Spayed, MC = Male Castrated.  

## References  
- Fefer, G., et al. (2022). *Longitudinal study on canine neuro-aging*. [DOI:https://doi.org/10.3390/ani13243846]  
- Panek, I., et al. (2020). *Plasma Amyloid Beta Concentrations in Aged and Cognitively Impaired Pet Dogs*. [DOI:https://doi.org/10.1007/s12035-020-02140-9]  
- Panek, I., et al. (2020b). *Plasma Neurofilament Light Chain as a Translational Biomarker of Aging and Neurodegeneration in Dogs*. [DOI:10.1007/s12035-020-01951-0]  



# Polysomnographic Studies in Dogs  

## Polysomnographic Studies  
The dogs underwent polysomnographic recordings, during which electroencephalogram (EEG), electrooculogram (EOG), electromyogram (EMG), and electrocardiogram (ECG) signals were simultaneously collected, following a slightly modified version of the protocol by [Reicher et al. (2020)](#references).  

### Electrode Placement and Setup  
- **F3** and **F4** (left and right frontal, respectively)  
- **Fz** (midline frontal)  
- **Cz** (vertex)  

This configuration was designed to capture activity in the frontal and parietal cortices. The EEG electrodes were referenced to an **Oz** electrode located over the external occipital protuberance.  

- **EOG**: Bipolar signals recorded from electrodes on the left and right zygomatic arches (near the lateral canthus of each eye).  
- **EMG**: Bipolar recordings from dorsal neck muscles (bilaterally placed electrodes).  
- **ECG**: Captured with an electrode over the fifth intercostal space (referenced to Cz).  

### Recording Equipment and Conditions  
All recordings used:  
- **Electrodes**: Gold-coated (Genuine Grass 10 mm Gold Cup, Natus Medical Inc).  
- **Securement**: SAC2 electrode cream (Cadwell Laboratories) after skin prep with Signa Spray (Parker Laboratories).  
- **Ground electrode**: Positioned over the left temporal muscles.  
- **Software**: Cadwell Easy II (Cadwell Laboratories).  

**Quality control**:  
- Electrode impedance kept below **20 kΩ**.  
- Sampling rate: **400 Hz**.  

**Environmental conditions**:  
- Quiet, dimly lit room with white noise.  
- Temperature maintained at **20°C**.  

### Study Protocol  
Owners brought their dogs for polysomnography on three separate days:  
1. **Adaptation day** (to minimize the ["first-night effect"]).  
2. **Two recording days** (with/without trazodone).  

**Comfort measures**:  
- Owners encouraged to bring familiar bedding (e.g., dog beds/blankets).  


#### Session Details:  
- **Adaptation**: 30-minute session to acclimate the dog.  
- **Recording days**:  
  - Two 2-hour sessions (order counterbalanced: with/without trazodone).  
  - Conducted between **12:30 PM–1:30 PM** (aligned with natural nap times).  
  - Dose: **5 mg/kg** (oral trazodone, per [Gilbert et al. (2016)](#references)).  
  - Minimum 2-week interval between adaptation and recording.  

**Note**: Sessions were paused if dogs showed anxiety or removed electrodes.  

---

## References  
- Reicher, V., et al. (2020). *Repeated afternoon sleep recordings indicate first‐night‐effect‐like adaptation process in family dogs*. [DOI:10.1111/jsr.12998]  
- Gilbert, R., et al. (2016). *Effects of trazodone on behavioral signs of stress in hospitalized dogs*. [DOI:https://doi.org/10.2460/javma.249.11.1281]  

