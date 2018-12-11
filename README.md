# Non-linear time-series research, Kepler data
### repository: kepler_nonlinear_research
Repository to joint project with IAA

[To be added: mono-fractal assessment]

Folder: **100_kepler_stars/**
- Each file is a CSV, wit columns:
    - Q: for the Kepler-quarter of the observation
    - nflux: normalized flux
    - nflux_err: normalized flux error, to be around 1
    - time: time in MJD
    - time_corr: error in time


Files derived from the Paz-Chinchon et al 2015](http://iopscience.iop.org/article/10.1088/0004-637X/803/2/69/meta) work:
* *final_KOI_literature_period_v03.csv*: stars from the KOI sample, with periods in the literature<sup>1</sup>
* *final_KCP_literature_period_v02.csv*: stars from the Kepler Confirmed Planetary Hosts list, with periods in the literature
* *final_KOI_results_all_v03.csv*: results for the period calculations, with some data coming from MCMC too.
* *final_KOI_results_and_Pinsonneault_v03.csv*: similar to the table of period calculations, but adding matches with Pinsonneault database of modeled mass, radius, and T_eff

Light curves selected from [Paz-Chinchon et al 2015](http://iopscience.iop.org/article/10.1088/0004-637X/803/2/69/meta)

**1**: revision not updated since the publication of the 2015 work
