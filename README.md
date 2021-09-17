# SOD.scripts
Scripts used in SOD ([Standerd Order of Data](http://www.seis.sc.edu/sod/)) to download seismograms in several formats (e.g., SAC, miniSEED.)
After downloading and installing [SOD](http://www.seis.sc.edu/downloads/sod/), we can run as:
```
$ sod -f test_sws.xml
```
## Notes
The default Data Center for catalog and seismogram is IRIS-DMC, SOme non-default Data Centers are shown as follows:
- **IRIS-DMC**: `service.iris.edu`
- **IRIS-DMC's PH5**: `service.iris.edu`
- **SCEDC**: `service.scedc.caltech.edu`
- **NCEDC**: `service.ncedc.org`
- **GEOFON**: `geofon.gfz-potsdam.de`
- **ETH**: `eida.ethz.ch`
- **RESIF**: `ws.resif.fr`
## Reference:
- **T. J. Owens, H. P. Crotwell, C. Groves, and P. Oliver-Paul**. (2004). SOD: Standing Order for Data. *Seismological Research Letters*, 75(4), 515-520, https://doi.org/10.1785/gssrl.75.4.515-a.
- [Seisman's SOD recipes](https://github.com/seisman/SODrecipes)
- [core-man's SOD recipes](https://github.com/core-man/SOD.recipes)

