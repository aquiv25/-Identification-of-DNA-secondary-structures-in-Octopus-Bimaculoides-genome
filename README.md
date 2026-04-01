# -Identification-of-DNA-secondary-structures-in-Octopus-Bimaculoides-genome

1)Article about Z-Hunter https://academic.oup.com/nargab/article/7/4/lqaf166/8332371?login=false
Web server Z-Hunter: https://bioinformatics.ibp.cz/#/analyse/zdna

2)Article about Z-GENIE https://link.springer.com/article/10.1186/s12864-025-12148-x
Web server https://i5h2oo-angel0i0garza0reyna.shinyapps.io/zgenie_shinyapp/

3)ZDNABert 
https://colab.research.google.com/github/mitiau/Z-DNABERT/blob/main/ZDNA-prediction.ipynb#scrollTo=urrTMPfMUrbP

4)Статья для референса https://pubmed.ncbi.nlm.nih.gov/37164635/

5)Блокнот 
https://colab.research.google.com/drive/1g43295fTtvBPQOOslrhOVmlwCV22VNaX?usp=sharing#scrollTo=h53qe4CIUnOb

6)Геном 
https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_001194135.2/

7)Курсовая за 2 курс https://docs.google.com/document/d/1qur-wk3HfM7wECVXFkZZxlJ9pxzggCPzrnyUej9YoKg/edit?tab=t.0

8)Задачи 
1 Полногеномная аннотация Z-DNABERT
2 Полногеномная аннотация Z-Hunt
3 Посмотреть, отличается ли Z-Hunter от Z-hunt - и м б лучше взять Z-Hunter
4. Построить Venn-diagram пересечений двух аннотаций
5. Построить распределение каждой аннотации (2) по геномным регионом и показать на слайде вместе с просто распределением регионов (круги как в Z-flipons. paper)

 
 
Распределение Z-ДНК по геномным регионам 
Promoters	2287424		
Exons		254224		
Introns		165150683		
Intergenic		159383862		
3UTR		5143		
5UTR		42627		
downstream		593683		

Тип региона       Всего          Уникальных                 Файл
------------------------------------------
✓ Promoters           27,030       23,224 intersection_promoters_dnabert.csv
✓ Exons               12,923        4,044  ZDNA_exons_bert.csv
✓ Introns          1,119,440      211,781     introns_bert.csv
✓ 5' UTR               1,263          194 intersection_5utr_bert.csv
✓ 3' UTR               1,162          171 intersection_3utr_bert.csv
✓ Downstream          20,422       16,939 intersection_down_bert.csv
✓ Intergenic       1,061,781      931,455  intergenic_bert.csv
