## Processing LIGO Data

This is a beginner project analysing gravitational wave data from LIGO.

Using Jupyter I plan to:
- Load public gravitational wave strain data (DONE)
- Generate a time-frequency spectrogram to visually identify the merger event (DONE, the merger event lines up with an observed spike visible on the CQT, but impossible to find on the STFT)
- Generate a sound file from the data to audibly hear the merger event

---

## Data and Sources

This project uses public gravitational wave data from the
Gravitational Wave Open Science Center (GWOSC), specifically the GWTC-3
catalog event **GW200224_222234**, based on data from the third observing
run (O3).

Data source:
https://gwosc.org/eventapi/html/GWTC-3-confident/GW200224_222234/v1/

---
### Acknowledgements and citations

R. Abbott et al. (LIGO Scientific Collaboration, Virgo Collaboration and KAGRA Collaboration), "Open data from the third observing run of LIGO, Virgo, KAGRA and GEO", [ApJS 267 29 (2023)](https://doi.org/10.3847/1538-4365/acdc9f) -- [INSPIRE](https://inspirehep.net/literature/2630216)

This research has made use of data or software obtained from the Gravitational Wave Open Science Center (gwosc.org), a service of the LIGO Scientific Collaboration, the Virgo Collaboration, and KAGRA. This material is based upon work supported by NSF's LIGO Laboratory which is a major facility fully funded by the National Science Foundation, as well as the Science and Technology Facilities Council (STFC) of the United Kingdom, the Max-Planck-Society (MPS), and the State of Niedersachsen/Germany for support of the construction of Advanced LIGO and construction and operation of the GEO600 detector. Additional support for Advanced LIGO was provided by the Australian Research Council. Virgo is funded, through the European Gravitational Observatory (EGO), by the French Centre National de Recherche Scientifique (CNRS), the Italian Istituto Nazionale di Fisica Nucleare (INFN) and the Dutch Nikhef, with contributions by institutions from Belgium, Germany, Greece, Hungary, Ireland, Japan, Monaco, Poland, Portugal, Spain. KAGRA is supported by Ministry of Education, Culture, Sports, Science and Technology (MEXT), Japan Society for the Promotion of Science (JSPS) in Japan; National Research Foundation (NRF) and Ministry of Science and ICT (MSIT) in Korea; Academia Sinica (AS) and National Science and Technology Council (NSTC) in Taiwan.
