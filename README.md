# hse22_hw5
[Работа в colab](https://colab.research.google.com/drive/1F6R6S1Y14ajA1dLZCZgCRufvcWYtiUxo?usp=sharing)
## Нормализация данных 
Transcripts Per Million (TPM) - это метод нормализации для RNA_seq, который следует читать как «на каждые 1 000 000 молекул РНК в образце РНК-секвенции x происходит из этого гена/транскрипта. Обычно имеет формулу:  
![TMP](pics/hw5_Tmp.png)  
Ho в нашем случае мы не будем учитывать длину l, поэтому формулой будет риды q делённые на сумму ридов и умноженные на миллион.
## Heatmap
![Heatmap](pics/hw5_1.png)  
По Heatmap'у можно уведеть формирование групп, значит они имеют один тип
## Визуализация UMAC и PCA
![UMAc](pics/hw5_2.png)
![PCA](pics/hw5_3.png)  
С помощью anndata и scanpy разбили данные на группы cTEC, mTEC-I, mTEC-II, mTEC-III, mTEC-IV.
