# vaping_moralizer
Official repo for the following two articles: 

1) "Moralization of E-cigarette Use and Regulation: A Mixed-Method Computational Analysis of Opinion Polarization," which has been published in _Health Communication_;

2) "Morally Driven and Emotionally Fueled: The Interactive Effects of Values and Emotions in the Social Transmission of Information Endorsing E-Cigarettes," which will be published in the _International Journal of Communication_ (IJoC). 

The code is modified from https://github.com/npmontgomery/moralizer.


Please cite as:

    Yunwen Wang, Yusi Aveva Xu, Jiaxi Wu, Hye Min Kim, Jessica L. Fetterman, Traci Hong, and Margaret L. McLaughlin. "Moralization of E-cigarette Use and Regulation: A Mixed-Method Computational Analysis of Opinion Polarization." Health Communication (2022): 1-11. https://doi.org/10.1080/10410236.2022.2027640 
    
    Wang et al. (2022)

## Description 

Vaping-Moralizer returns word counts of a text based on the [Moral Foundations Vocabulary 2.0](https://osf.io/ezn37/) and our [Vaping dictionary](https://github.com/wang-yunwen/vaping_moralizer/blob/main/vaping_dict.txt)

## Installation

We have provided the envinroment file for conda users. 
```shell
conda env create -f environment.yml
conda activate vaping-moralizer
```
Installing en_core_web_sm by using
```shell
python -m spacy download en_core_web_sm
```

## Usage

Please see [usage_sample.ipynb](https://github.com/wang-yunwen/vaping_moralizer/blob/main/usage_sample.ipynb) for reference. 



