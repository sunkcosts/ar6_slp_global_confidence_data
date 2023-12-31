# ar6_slp_global_confidence_data

## Note: Reformatting

The original data is in a somewhat suboptimal netCDF format. I've cleaned it here and converted into a custom `.ssp` format - which is really just JSON without the `.json` extension. Should be much easier to work with. If you want to follow along with the reformatting notebook just make sure to install the requirements first:

```
pip install -r requirements.txt
```

Also, credit to [this article](https://towardsdatascience.com/read-netcdf-data-with-python-901f7ff61648) by Konrad Hafen for the netcd4 parsing stuff.

## Description

This repository contains data for sea level rise projections from the IPCC AR6 report. It is duplicated here, as I'm adding the data to a package, but implementing automated data downloads in that package for package files doesn't work on zenodo, but it does on github.

Specifically, the data maintained here is only a sample of the `ar6/global/confidence_output_files/*` in the dataset which can be found at the link below.

## Links

- Paper: https://zenodo.org/records/5914710
- Download link: https://zenodo.org/records/5914710/files/ar6.zip?download=1


## Source

### License (of source)

> IPCC AR6 Licensing: The IPCC AR6 Sea-Level Rise Projections are licensed by the authors under a Creative Commons Attribution 4.0 International License (https://creativecommons.org/licenses/). The data producers and data providers make no warranty, either express or implied, including, but not limited to, warranties of merchantability and fitness for a particular purpose. All liabilities arising from the supply of the information (including any liability arising in negligence) are excluded to the fullest extent permitted by law.


### Citation (for source)

We thank the projection authors for developing and making the sea-level rise projections available, multiple funding agencies for supporting the development of the projections, and the NASA Sea-Level Change Team for developing and hosting the IPCC AR6 Sea-Level Projection Tool.

For more info, please see chapter 9 of Working Group 1 contribution to the the IPCC Sixth Assessment Report, the Framework for Assessment of Changes To Sea-level (FACTS) model description paper, and the version of the data set used:

Fox-Kemper, B., H. T. Hewitt, C. Xiao, G. Aðalgeirsdóttir, S. S. Drijfhout, T. L. Edwards, N. R. Golledge, M. Hemer, R. E. Kopp, G. Krinner, A. Mix, D. Notz, S. Nowicki, I. S. Nurhati, L. Ruiz, J-B. Sallée, A. B. A. Slangen, Y. Yu, 2021, Ocean, Cryosphere and Sea Level Change. In: Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [Masson-Delmotte, V., P. Zhai, A. Pirani, S. L. Connors, C. Péan, S. Berger, N. Caud, Y. Chen, L. Goldfarb, M. I. Gomis, M. Huang, K. Leitzell, E. Lonnoy, J. B. R. Matthews, T. K. Maycock, T. Waterfield, O. Yelekçi, R. Yu and B. Zhou (eds.)]. Cambridge University Press. In press.

Garner, G. G., R. E. Kopp, T. Hermans, A. B. A. Slangen, G. Koubbe, M. Turilli, S. Jha, T. L. Edwards, A. Levermann, S. Nowikci, M. D. Palmer, C. Smith, in prep. Framework for Assessing Changes To Sea-level (FACTS). Geoscientific Model Development.

Garner, G. G., T. Hermans, R. E. Kopp, A. B. A. Slangen, T. L. Edwards, A. Levermann, S. Nowikci, M. D. Palmer, C. Smith, B. Fox-Kemper, H. T. Hewitt, C. Xiao, G. Aðalgeirsdóttir, S. S. Drijfhout, T. L. Edwards, N. R. Golledge, M. Hemer, R. E. Kopp, G. Krinner, A. Mix, D. Notz, S. Nowicki, I. S. Nurhati, L. Ruiz, J-B. Sallée, Y. Yu, L. Hua, T. Palmer, B. Pearson, 2021. IPCC AR6 Sea-Level Rise Projections. Version 20210809. PO.DAAC, CA, USA. Dataset accessed [YYYY-MM-DD] at https://podaac.jpl.nasa.gov/announcements/2021-08-09-Sea-level-projections-from-the-IPCC-6th-Assessment-Report.



### Acknowledgements (from source)

    The development of the sea-level rise projections was supported by multiple funders, including:

    * U.S. National Aeronautics and Space Administration (grants 80NSSC17K0698, 80NSSC20K1724 and 80NSSC21K0322 and JPL task 105393.509496.02.08.13.31)

    * U.S. National Science Foundation (grant ICER-1663807)

    * U.K. Natural Environment Research Council (grant NE/T009381/1)

    * NIOZ Royal Netherlands Institute for Sea Research

    * PROTECT, which has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement no. 869304

    * UK Natural Environment Research Council grant NE/T007443/1.

    We acknowledge the World Climate Research Programme, which, through its Working Group on Coupled Modelling, coordinated and promoted CMIP6. We thank the climate modeling groups for producing and making available their model output, the Earth System Grid Federation (ESGF) for archiving the data and providing access, and the multiple funding agencies who support CMIP6 and ESGF.