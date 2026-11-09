# Southern DES ultra diffuse galaxy catalog

`des_south_udg_6764.csv` is the full data for Table 4 (Appendix B) of *A Deep-Learning Search for Ultra-Diffuse Galaxy Candidates in the Dark Energy Survey: Southern Extension and Statistical Analysis*. It contains 6,764 targets from the southern DES search after removing six objects shared with the northern catalog of Su et al. (2026). The catalog includes 66 UDGs with adopted spectroscopic redshifts and physical effective radii above 1.5 kpc and 6,698 candidates selected by photometry and visual morphology.

Photometry is from DES DR2 (Abbott et al. 2021, ApJS, 255, 20, doi:10.3847/1538-4365/ac00b3). The file is comma-delimited ASCII with a header row. Blank entries denote missing measurements. Physical radii use H0 = 70 km/s/Mpc, Omega_M = 0.3, and Omega_Lambda = 0.7.

| Column | Type | Unit | Description |
| --- | --- | --- | --- |
| `coadd_object_id` | integer | --- | DES DR2 coadded-source identifier. |
| `ra_deg` | decimal | deg | Right ascension of the DES source (J2000). |
| `dec_deg` | decimal | deg | Declination of the DES source (J2000). |
| `mag_auto_g` | decimal | mag | DES DR2 g-band MAG_AUTO (AB). |
| `mag_auto_i` | decimal | mag | DES DR2 i-band MAG_AUTO (AB). |
| `g_minus_i` | decimal | mag | Difference between g- and i-band MAG_AUTO. |
| `axis_ratio` | decimal | --- | Projected minor-to-major axis ratio b/a. |
| `re_g_arcsec` | decimal | arcsec | DES DR2 g-band half-light radius converted to arcseconds. |
| `mu_e_g` | decimal | mag arcsec^-2 | Mean effective surface brightness in the g band, as in Equation (1). |
| `morphology_class` | string | --- | Visual classification, AS (smooth) or AUS (unsmooth). |
| `z_spec` | decimal | --- | Adopted spectroscopic redshift. |
| `re_g_kpc` | decimal | kpc | Physical effective radius derived from the g-band angular radius and angular diameter distance. |
