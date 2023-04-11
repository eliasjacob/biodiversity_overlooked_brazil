# Dictionary for the dataset:

| Column                       | Description                              | Data Type | Example Values                              |
|:-----------------------------|:-----------------------------------------|:----------|:--------------------------------------------|
| **gender**                   | Gender of the individual                 | String    | M, F                                        |
| **food_insecurity**          | Food insecurity level (1 to 4)           | Integer   | 1, 2, 3                                     |
| **food_insecurity_description** | Description of the food insecurity level | String    | seguranca alimentar, insegurança leve, insegurança moderada |
| **race**                     | Race of the individual                   | String    | branca, preta, parda, amarela, indígena     |
| **urbanization**             | Urbanization level (1 for urban areas, 2 for rural areas) | Integer | 1, 2                                 |
| **urban_description**        | Description of urbanization level        | String    | urbano, rural                               |
| **state**                    | Name of the Brazilian state              | String    | Paraíba, Piauí, Paraná, Rio Grande do Norte |
| **income**                   | Monthly income of the individual in reais | Float     | 339.63, 252.01, 1072.54, 2806.49            |
| **age**                      | Age of the individual in years           | Integer   | 15, 16, 72, 50                              |
| **years_schooling**          | Number of years of schooling             | Integer   | 9, 5                                        |
| **ate_ufp**                  | Consumption of unconventional food plants (1=yes, 0=no) | Integer | 1, 0                                  |
| **is_male**                  | Boolean flag indicating if the individual is male (1=yes, 0=no) | Integer | 1, 0                                |
| **region**                   | Name of the Brazilian region             | String    | Nordeste, Sul, Centro Oeste                |
| **is_caucasian**             | Boolean flag indicating if the individual is Caucasian (1=yes, 0=no) | Integer | 1, 0                              |
| **is_rural**                 | Boolean flag indicating if the individual lives in Rural areas (1=yes, 0=no) | Integer | 1, 0                            |

Shape: 1,545 rows, 15 columns