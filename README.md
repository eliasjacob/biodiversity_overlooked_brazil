# Biodiversity is Overlooked in the Diets of Different Social Groups in Brazil  
## This repository includes the code and data necessary to replicate the Machine Learning results presented in the research paper.

[![Paper](https://zenodo.org/badge/doi/10.1038/s41598-023-34543-8.svg)]([https://doi.org/10.1371/journal.pone.XXX](https://doi.org/10.1038/s41598-023-34543-8))


 
## Description   
Food biodiversity is essential for improving nutrition and reducing hunger in populations worldwide. However, in middle and low-income countries, the biodiversity of food production does not necessarily represent food consumption patterns by population. We used Brazil, one of the world's megabiodiverse countries, as a case study to investigate the following questions: what is the prevalence of consumption of biodiverse foods in Brazil, and what are the socioeconomic factors that influence their consumption throughout the country? We used data from a Brazilian representative national dietary survey to estimate the frequency of food consumption of unconventional food plants, edible mushrooms, and wild meat, in according to socioeconomic variables. Thus, we investigated the socioeconomic predictors of Unconventional Food Plants consumption using methods of Machine Learning (ML) and multiple zero-inflated Poisson (ZIP) regression. We showed that biodiverse food consumption in Brazil is low, just related by 1.3% of the population, varying in according to area, ethnicity, age, food insecurity, sex, and educational level. Our findings of low utilization of biodiversity suggest an important mismatch between the rich biodiversity of the country and its representation in the human diet.


## How to run   
1 - Clone this project

2 - Install the environment

```bash
cd paper_biodiversity_overlooked
conda env create --file environment.yaml
conda activate paper_biodiversity_overlooked
```

3 - Run the notebooks on the folder `notebooks/`


### Citation   
```
@ARTICLE{Gomes2023-et,
  title    = "Biodiversity is overlooked in the diets of different social
              groups in Brazil",
  author   = "Gomes, S{\'a}vio Marcelino and Chaves, Viviany Moura and de
              Carvalho, Aline Martins and da Silva, Elenilma Barros and de
              Menezes Neto, Elias Jacob and de Farias Moura, Gabriela and da
              Silva Chaves, Leonardo and Alves, R{\^o}mulo Romeu N{\'o}brega
              and de Albuquerque, Ulysses Paulino and de Oliveira Pereira,
              Fillipe and Jacob, Michelle Cristine Medeiros",
  abstract = "Food biodiversity is essential for improving nutrition and
              reducing hunger in populations worldwide. However, in middle and
              low-income countries, the biodiversity of food production does
              not necessarily represent food consumption patterns by
              population. We used Brazil, one of the world's megabiodiverse
              countries, as a case study to investigate the following
              questions: what is the prevalence of consumption of biodiverse
              foods in Brazil, and what are the socioeconomic factors that
              influence their consumption throughout the country? We used data
              from a Brazilian representative national dietary survey to
              estimate the frequency of food consumption of unconventional food
              plants, edible mushrooms, and wild meat, in according to
              socioeconomic variables. Thus, we investigated the socioeconomic
              predictors of Unconventional Food Plants consumption using
              methods of Machine Learning (ML) and multiple zero-inflated
              Poisson (ZIP) regression. We showed that biodiverse food
              consumption in Brazil is low, just related by 1.3\% of the
              population, varying in according to area, ethnicity, age, food
              insecurity, sex, and educational level. Our findings of low
              utilization of biodiversity suggest an important mismatch between
              the rich biodiversity of the country and its representation in
              the human diet.",
  journal  = "Scientific Reports",
  volume   =  13,
  number   =  1,
  pages    = "7509",
  month    =  may,
  year     =  2023
}

```   
