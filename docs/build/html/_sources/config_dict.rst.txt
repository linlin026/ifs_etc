Configuation Dictionary Structure
=================================


* instrument
    * readout_xbin: 1,
    * readout_ybin":1,
    * gain":1,
    * dark":0.017,
    * readout_noise":4.0,
    * QE":1.0,
    * efficiency_file":"IFU_throughput.dat",
    * ccd_xsize":1.755555,
    * ccd_ysize":0.1,
    * extract_aper_width":2,
    * spaxel_xsize":0.2,
    * spaxel_ysize":0.2,
    * fov_xsize":6,
    * fov_ysize":6,
    * wave_start":3500,
    * wave_end":10000,
    * wave_delta: 1.755555

* calc_mode
    * mode":2,
    * repn":20,
    * obst":300.0

* source
    * position
        * x_offset":0.0,
        * y_offset":0.0

    * geometry
        * shape":"PSF",
        * FWHM":0.2

    * spectrum
        * name":"/Users/linlin/anaconda3/lib/python3.7/site-packages/ifs_etc/refdata/sed/SFgal_texp_FeH0_tau1_Ewd.fits",
        * redshift":0.0,
        * ebv":0.0

    * normalization
        * value":17.7,
        * unit":"AB magnitude",
        * band":"sdss_g"


* background
    * zodiacal":"med",
    * earth_shine":"med"
