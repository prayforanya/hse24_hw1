# hse24_hw1
Ссылка на ноутбук https://colab.research.google.com/drive/1ZBy9oDJPre2wdtpKQ3dlTt4G2NeE5y1B?usp=sharing 
Скачала файл SRR5836473_1.fastq и провела его анализ с помощью FASTQC (отчет лежит в папке data)

Необычное распределение GC может быть связано с бисульфитным секвенированием, так как во время него неметелированный Цитозин переходит в Урацил. C меняется на U.

![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/per_sequence_gc_content.png)

Полученная таблица:

| Файл | Стадия развития | Чтения на 11347700-11367700 | Чтения на 40185800-40195800 | Процент дупликации |
| - | - | - | - | - |
| SRR5836473 | 8 cell   | 551 | 194 | 18.28 % |
| SRR3824222 | Epiblast | 1344 | 565 | 2.91 % |
| SRR5836475 | ICM      | 797 | 274 | 9.07 % |

MBIAS PLOT (отчеты лежат в папке data)

8cell – 8-клеточный эмбрион, примерно 2.25 дня после оплодотворения яйцеклетки
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/8_cell_Read_1.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/8_cell_Read_2.png)

ICM – внутренняя клеточная масса бластоциста, примерно 3.5 дня после оплодотворения яйцеклетки

![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/icm_Read_1.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/icm_Read_2.png)

Epiblast – стадия эпибласта, примерно 6.5 дней после оплодотворения яйцеклетки
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/epiblast_Read_1.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/epiblast_Read_2.png)

Гистограммы
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/reference.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/8_cell.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/icm.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/epiblast.png)

Уровень метелирования и покрытия
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/image_cov.png)
![image](https://github.com/prayforanya/hse24_hw1/blob/main/data/image_met.png)
