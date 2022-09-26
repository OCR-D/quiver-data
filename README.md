# OCR-D Quiver Data

This repository provides the Ground Truth data for the [OCR-D Quiver back end](https://github.com/OCR-D/quiver-back-end.git).
This data serves as a basis for benchmarking the performance and accuracy of different OCR-D workflows for different types of input data.

Currently the Ground Truth data has been selected according to the following characteristics:

* century of creation
* fonts used
* layout (simple vs. complex)

Only works that have both layout and text Ground Truth available have been added to the corpus.

In some cases several works have been merged into one "meta" work in order to have more data at hand and to consider heterogeneous material.

## Detailed overview of the data

### 16th century, fraktur, simple layout

* kistler_kraeuter_1500.ocrd + trota_mordtbrenner_1540.ocrd + luther_auszlegunge_1520.ocrd

### 16th century, fraktur, complex layout

* *two-columned*: luther_babstum_1526.ocrd
* *hand-written additions, stamps*: petrarca_psalmi_1506.ocrd + nn_lied_1520.ocrd
* *partly tabular-like structures, stamps*: aventinus_grammatica_1515.ocrd
* *labelled illustration, initial, stamps*: nn_historia_1500.ocrd

### 16th century, antiqua, simple layout

* heyden_paedono_1548.ocrd

### 16th century, antiqua, complex layout

* *marginal notes [both printed and hand written], initial*: alberti_pictura_1540.ocrd

### 16th century, font mix, simple layout

* -n/a-

### 16th century, font mix, complex layout

* -n/a-

---

### 17th century, fraktur, simple layout

* calvi_beutelschneider01_1627.ocrd

### 17th century, fraktur, complex layout

* *musical notation*: silesius_seelenlust01_1657.ocrd
* *hand-written additions, with title page*: huebner_handbuch_1696.ocrd

### 17th century, antiqua, simple layout

* -n/a-

### 17th century, antiqua, complex layout

* -n/a-

### 17th century, font mix, simple layout

#### fraktur, antiqua

* rollenhagen_reysen_1603.ocrd + loeber_heuschrecken_1693.ocrd + bohse_helicon_1696.ocrd *(feat. initials, with title page, colour chart)*

#### fraktur, antiqua, ancient Greek, Hebrew

* weigel_gnothi02_1618.ocrd + dannhauer_catechismus10_1673.ocrd

### 17th century, font mix, complex layout

#### fraktur, antiqua

* *partly two-columned, initials*: glauber_opera01_1658.ocrd
* *partly two-columned, initials, marginal notes*: arnold_ketzerhistorie01_1699.ocrd
* *tabular-like layout*: lohenstein_agrippina_1665.ocrd
* *marginal notes, initials*: meyfart_rhetorica_1634.ocrd
* *initials, hand-written additions*: valentinus_occulta_1603.ocrd

---

### 18th century, fraktur, simple layout

* lessing_menschengeschlecht_1780.ocrd

### 18th century, fraktur, complex layout

* *marginal notes*: justi_abhandlung01_1758.ocrd + estor_rechtsgelehrsamkeit02_1758.ocrd
* *partly two-columned*: buerger_gedichte_1778.ocrd
* *tables, mathematics*: euler_rechenkunst01_1738.ocrd
* *handwritten additions*: nn_besuch_1780.ocrd
* *with title page, stamps*: luz_blitz_1784.ocrd + bernd_lebensbeschreibung_1738.ocrd

### 18th century, antiqua, simple layout

* ballenstedt_delatio_1777.ocrd

### 18th century, antiqua, complex layout

* -n/a-

### 18th century, font mix, simple layout

* -n/a-

### 18th century, font mix, complex layout

* *partly two-columned, intial*: benner_herrnhuterey04_1748.ocrd

---

### 19th century, antiqua [1]

* blumenbach_anatomie_1805.ocrd

### 19th century, fraktur [1]

* arnimb_goethe03_1835.ocrd

[1] We only have two works with text GT for the 19th century, blumenbach_anatomie_1805.ocrd and arnimb_goethe03_1835.ocrd. Since the 19th century isn't part of our scope, we'll limit ourselves to the material we already have.
