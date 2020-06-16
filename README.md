# CHLA and TSS inference through Machine Learning 
This repository features a Machine Learning and Remote Sensing technique to predict the concentration of Chlorophyll-a and Total Suspended Solid in water bodies.

This method was developed by [Vizlab | X-Reality and GeoInformatics Lab](http://www.vizlab.unisinos.br/) as an alternative to monitor Total Suspended Solids (TSS) and chlorophyll-a concentration, two critical parameters to monitor water quality. Since directly collecting samples for laboratory analysis can be expensive, this methodology estimates this information through remote sensing and Machine Learning (ML) techniques. This method was accessed and evaluated separately in two study areas, where both TSS and chlorophyll-a models achieved R-squared values above 0.8

<p align="center">
<img src="https://www.mdpi.com/sensors/sensors-20-02125/article_deploy/html/images/sensors-20-02125-g006-550.jpg" width="600" alt="Results"> 
</p>

## Published articles 
For a more in-depth understanding of the method, please consider reading the published paper below that employed and validated this method. To cite each of them please consult the How to cite section.

[A Method for Chlorophyll-a and Suspended Solids Prediction through Remote Sensing and Machine Learning](https://doi.org/10.3390/s20072125)

Authors: [Lucas Silveira Kupssinskü](https://www.researchgate.net/profile/Lucas_Kupssinskue), [Tainá Thomassim Guimarães](https://www.researchgate.net/profile/Taina_Guimaraes), [Eniuce Menezes de Souza](https://www.researchgate.net/profile/Eniuce_Souza), [Daniel C. Zanotta](https://www.researchgate.net/profile/Daniel_Zanotta), [Mauricio Roberto Veronez](https://www.researchgate.net/profile/Mauricio_Veronez) and [Luiz Gonzaga, Jr](https://www.researchgate.net/profile/Luiz_Gonzaga_da_Silveira_Jr) 

Published in: [Sensors MDPI](https://www.mdpi.com/journal/sensors/special_issues/ICST2019)

# Table of contents 

- [Requirements](#requirements) 
- [Usage](#usage) 
- [How to cite](#how-to-cite) 
- [Credits](#credits) 
- [License](#license) 

## Requirements

``` 
numpy
pandas
sklearn
keras
scipy
seaborn
matplotlib
``` 

## Usage
This code is ready to run on google colab environment, the data is also avaliable in this repository. Just follow the link bellow and import the xls data files into your environment.

[![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/blue?icon=terminal)](https://colab.research.google.com/github/lucaskup/TSS_ChlorophyllA_Prediction/blob/master/MDPI_Sensors_Chlorophilla.ipynb)

## How to cite

If you find our work useful in your research please consider citing our paper:
```
@article{Silveira_Kupssinsk__2020, 
  title={A Method for Chlorophyll-a and Suspended Solids Prediction through 
         Remote Sensing and Machine Learning}, 
  volume={20}, 
  ISSN={1424-8220}, 
  url={http://dx.doi.org/10.3390/s20072125}, 
  DOI={10.3390/s20072125}, 
  number={7}, 
  journal={Sensors}, 
  publisher={MDPI AG}, 
  author={Silveira Kupssinskü, Lucas and 
          Thomassim Guimarães, Tainá and 
          Menezes de Souza, Eniuce and 
          C. Zanotta, Daniel and 
          Roberto Veronez, Mauricio and 
          Gonzaga, Luiz and 
          Mauad, Frederico Fábio}, 
  year={2020}, 
  month={Apr}, 
  pages={2125}
}
  ```


## Credits
This work is credited to the [Vizlab | X-Reality and GeoInformatics Lab](http://www.vizlab.unisinos.br/) and the following authors and developers: [Lucas Silveira Kupssinskü](https://www.researchgate.net/profile/Lucas_Kupssinskue) and [Tainá Thomassim Guimarães](https://www.researchgate.net/profile/Taina_Guimaraes)


## License
``` 
MIT Licence (https://mit-license.org/) 
``` 



