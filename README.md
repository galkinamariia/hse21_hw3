# hse21_hw3
### Введение
Целью данного задания является сравнение RNA-seq данных перепрограммированных и неперепрограммированных (контрольных) мышиных эмбриональных фибробластов (MEFs) и нахождение генов, которые наиболее сильно изменяют свою экспрессию в этом процессе.

Ссылка на мой первый google colab: https://colab.research.google.com/drive/1Z_usMhFuSfnMnPAVMf9EieIy2-uS2pwO?usp=sharing
 
 ### Часть №1 ДЗ№3
 
> Полученные в ходе выполнения ДЗ№3 статистики из MultiQC:

  <img src="/pictures/fastqc_sequence_counts_plot.png " width="600" />
  <img src="/pictures/fastqc_per_sequence_quality_scores_plot.png" width="600" />
  <img src="/pictures/fastqc_per_base_sequence_quality_plot.png" width="600" />
  <img src="/pictures/fastqc_sequence_duplication_levels_plot.png" width="600" />
 
 > Результатом первой части задания является сводная таблица ALL.counts, где указано количество чтений уникально-картированных на каждый ген в каждом образце следующего вида:
 
    Число чтений для SRR3414629: 16049609
    
    Число чтений для SRR3414630: 11465324
    
    Число чтений для SRR3414631: 18408851
    
    Число чтений для SRR3414635: 10791658
    
    Число чтений для SRR3414636: 15757580
    
    Число чтений для SRR3414637: 15736978
 
 ### Часть №2 ДЗ№3
 > Ссылка на второй google colab: https://colab.research.google.com/drive/1OGBB9wsmZ55oty3FxfzwGzG41QIsYY2p?usp=sharing
 
 ### Графики из анализа DESeq2:
 
 > 1. MA-plot:
 
 <img src="/pictures/plotma.png " width="600" />
 
 > 2. Тепловая карта:
 
 <img src="/pictures/heatmap.png " width="600" />
 
 > 3. Графики со значениями "Normalized counts" в контрольных и перепрограммированных образцах:
 
  <img src="/pictures/res1.png " width="600" />
  <img src="/pictures/res2.png" width="600" />
  <img src="/pictures/res3.png " width="600" />
  <img src="/pictures/res4.png" width="600" />
