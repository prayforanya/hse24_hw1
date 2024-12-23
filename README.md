# hse24_hw1

##### Ссылка на ноутбук https://colab.research.google.com/drive/1ZBy9oDJPre2wdtpKQ3dlTt4G2NeE5y1B?usp=sharing 

Скачала файл SRR5836473_1.fastq и провела его анализ с помощью FASTQC (отчет лежит в папке data)

Необычное распределение GC может быть связано с бисульфитным секвенированием, так как во время него неметелированный Цитозин переходит в Урацил. C меняется на U.

![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/per_sequence_gc_content.png)
 
Содержание Цитозина должно быть равно содержанию Гуанина (из комплемаентарности), а содержание Тимина примерно соответсвовать содержанию Аденина. Однако Тимина (Урацила) больше чем должно быть, следовательно можно сделать вывод о том, что некоторые Тимины до секвенирования были Цитозином, следовательно значительная часть Цитозина была неметелирована (но не весь).

![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/per_base_sequence_content.png)

Полученная таблица:

| Файл | Стадия развития | Чтения на 11347700-11367700 | Чтения на 40185800-40195800 | Процент дупликации |
| - | - | - | - | - |
| SRR5836473 | 8 cell   | 551 | 194 | 81.72 % |
| SRR3824222 | Epiblast | 1344 | 565 | 97.09 % |
| SRR5836475 | ICM      | 797 | 274 | 90.93 % |

### MBIAS PLOT (отчеты лежат в папке data)

8cell – 8-клеточный эмбрион, примерно 2.25 дня после оплодотворения яйцеклетки
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/8_cell_Read_1.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/8_cell_Read_2.png)

ICM – внутренняя клеточная масса бластоциста, примерно 3.5 дня после оплодотворения яйцеклетки

![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/icm_Read_1.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/icm_Read_2.png)

Epiblast – стадия эпибласта, примерно 6.5 дней после оплодотворения яйцеклетки
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/epiblast_Read_1.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/epiblast_Read_2.png)

Сильнее всего метелирован epiblast, а слабее icm, это соответвсвует данным из литературы

### Гистограммы
Полученные диаграммы похожи на референс
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/reference.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/8_cell.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/icm.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/epiblast.png)

### Уровень метелирования и покрытия
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/image_cov.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/image_met.png)
