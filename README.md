# hse22_project_minor

### Ссылка на colab
https://colab.research.google.com/drive/1rkh9LTjdhWXzfEFQ9a0T_ZY32Cw93OEA?usp=sharing

## Геномы и Z-DNA

|  Образец    | Кол. последовательностей | Длина генома  | Кол. генов | Доля генов | Кол. Z-dna>500| Общая длина Z-dna>500 |
|:-----------:|:------------|:----------------|:------------------|:-------------- |---|---|
| Cellulomonas fimi ATCC 484       | 1 | 4266344 | 3871 | 0.90158553 | 36858 | 484888 |
| Cellulomonas flavigena DSM 20109 | 1 | 4123179 | 3760 | 0.90175663 | 35484 | 467186 |
| Cellulomonas gilvus ATCC 13127   | 1 | 3526441 | 3248 | 0.91277438 | 33080 | 446507 |
| Cellulomonas iranensis           | 1 | 4046676 | 3638 | 0.89839636 | 43205 | 588917 |
| Cellulomonas shaoxiangyii        | 1 | 3909366 | 3504 | 0.9004941  | 35658 | 479625 |

![Alt text](/imgs/zdna.png?raw=true "Optional Title")

##  Кластеры и Z-DNA

Всего выявлено 3637 кластеров.

![Alt text](/imgs/hist.png?raw=true "Optional Title")

Были выбраны следующие из них:

| Кластер | Кол. генов | Функция | расположение Z-DNA | ср. знач. Z-DNA score |
|:-----------:|:------------|:----------------|:------------------|:-------------- |
| 1990 | 7 | thioredoxin-disulfide reductase activity | В начале и второй половине гена | 11590 |
| 1461 | 8 | ATP-binding | Преимущественно в конце, немного в начале | 8003 |
| 1843 | 7 | gluconokinase, Carbohydrate transport and metabolism | В основном в середине гена | 9943 |
| 127 | 7 | ABC transporter ATP-binding protein | В начале и конце гена | 11321 |
| 2143 | 7 | ABC transporter ATP-binding protein | В основном в конце и немного в начале | 23660 |

Выравнивание производилось с помощью [muscle](https://www.ebi.ac.uk/Tools/msa/muscle/. "MUSCLE 3.8"):

Кластер 1990:
![Alt text](/imgs/1990.png?raw=true "Optional Title")

Кластер 1461:
![Alt text](/imgs/1461.png?raw=true "Optional Title")

Кластер 1843:
![Alt text](/imgs/1843.png?raw=true "Optional Title")

Кластер 127:
![Alt text](/imgs/127.png?raw=true "Optional Title")

Кластер 2143:
![Alt text](/imgs/2143.png?raw=true "Optional Title")

Визуализация расположения Z-DNA относительно генов:

Кластер 1990:
![Alt text](/imgs/zdna1990.png?raw=true "Optional Title")

Кластер 1461:
![Alt text](/imgs/zdna1461.png?raw=true "Optional Title")

Кластер 1843:
![Alt text](/imgs/zdna1843.png?raw=true "Optional Title")

Кластер 127:
![Alt text](/imgs/zdna127.png?raw=true "Optional Title")

Кластер 2143:
![Alt text](/imgs/zdna2143.png?raw=true "Optional Title")
