# Non-linear time-series research, Kepler data
### repository: kepler_nonlinear_research
Repository to joint project with IAA

Files derived from the [Paz-Chinchon et al 2015](http://iopscience.iop.org/article/10.1088/0004-637X/803/2/69/meta) work:
* *final_KOI_literature_period_v03.csv*: stars from the KOI sample, with periods in the literature<sup>1</sup>
* *final_KCP_literature_period_v02.csv*: stars from the Kepler Confirmed Planetary Hosts list, with periods in the literature
* *final_KOI_results_all_v03.csv*: results for the period calculations, with some data coming from MCMC too.
* *final_KOI_results_and_Pinsonneault_v03.csv*: similar to the table of period calculations, but adding matches with Pinsonneault database of modeled mass, radius, and T_eff
* Files in  **100_kepler_stars/** Each file is a CSV, with columns:
    - Q: for the Kepler-quarter of the observation
    - nflux: normalized flux
    - nflux_err: normalized flux error, to be around 1
    - time: time in MJD
    - time_corr: error in time
* **boxc2dim_D.csv**: results from 2D boxcounting on the reduced version of the LCs, namely, using 1/2 of the data points. Columns are:
    - D_m_bias, D_b_bias, D_rval_bias, D_pval_bias, D_stderr_bias, D_m, D_b, D_rval, D_pval, D_stderr
    - D_m is the (mono) fractal dimension
* **boxc2dim_lacunarity.csv**: results from 2D boxcounting on the reduced version of the LCs, namely, using 1/2 of the data points. The lacunarity was calculated using the traditional method from Plotnick et al 1996. Columns are:
    - Lac_m_bias, Lac_b_bias, Lac_rval_bias, Lac_pval_bias, Lac_stderr_bias, Lac_m, Lac_b, Lac_rval, Lac_pval, Lac_stderr
    - Note no single linear regression accounts for the lacunarity behavior


NOTES:

    Light curves selected from [Paz-Chinchon et al 2015](http://iopscience.iop.org/article/10.1088/0004-637X/803/2/69/meta)

______________________________________________________________________
**1**: revision not updated since the publication of the 2015 work
