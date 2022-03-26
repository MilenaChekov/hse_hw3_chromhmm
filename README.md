# hse_hw3_chromhmm

https://colab.research.google.com/drive/1OH53l6RjINW6nLAQfMe68xWRAZVJNlIh?usp=sharing - ссылка на гугл коллаб

Метка - Файл
1. H3k4me3 - http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneK562H3k4me3StdAlnRep1.bam
2. H3k4me2 - http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneK562H3k4me2StdAlnRep1.bam
3. H3k4me1 - http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneK562H3k4me1StdAlnRep1.bam
4. H3k79me2 - http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneK562H3k79me2StdAlnRep1.bam
5. H4k20me1 - http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneK562H4k20me1StdAlnRep1.bam
6. H3k36me3 - http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneK562H3k36me3StdAlnRep1.bam
7. H3k9me3 - http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneK562H3k9me3StdAlnRep1.bam
8. H3k9ac - http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneK562H3k9acStdAlnRep1.bam 
9. H3k27ac - http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneK562H3k27acStdAlnRep1.bam
10. Lsd1 - http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneK562Lsd1AlnRep1.bam
11. Контроль - http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneK562ControlStdAlnRep1.bam


cellmarkfiletable.txt 
<img width="475" alt="Снимок экрана 2022-03-26 в 19 43 14" src="https://user-images.githubusercontent.com/60537367/160249168-736cab17-3c65-4548-9d66-f6775ba0e3b3.png">


<img width="384" alt="Снимок экрана 2022-03-26 в 20 34 51" src="https://user-images.githubusercontent.com/60537367/160250890-4e8d4500-7f45-430e-9c99-60c21ab16191.png">
<img width="398" alt="Снимок экрана 2022-03-26 в 20 35 14" src="https://user-images.githubusercontent.com/60537367/160250906-1a84848f-429e-4abd-917e-80856abd0346.png">

<img width="1019" alt="Снимок экрана 2022-03-26 в 20 55 05" src="https://user-images.githubusercontent.com/60537367/160251554-d0418e0f-b2b7-4a6b-a859-e16b1e4b14c0.png">
<img width="1015" alt="Снимок экрана 2022-03-26 в 21 01 22" src="https://user-images.githubusercontent.com/60537367/160251829-c4d43cbb-ba1c-43f7-8b6e-01f734146be5.png">


"1" предположительно более слабый промотер, так как идет более короткими кчастками после "2", также менее выражены CpG островки и TSS. "2", соответственно, активный промотер: идет в начале гена, выражены CpG островки и TSS. Также многочисленные модификации, которые ассоциированны с данными состояниями, ассоцирированы именно с промотерами. Например, H3K4me3, отвечает за низкий уровень метилирования (собственно, промотеры низкометилированные, с cpg островками)[1]. "3" выглядит как слабый/ неактивный промотер (маленькие участки в начале гена), возможно артефакт, часто чередуется с 4. 

"1" выглядит как слабо транскрибируемая ДНК (длинные участки, достаточно большой процент хромосомы). "2" - это гетерохроматин (наибольший процент аннотированного генома представлен гетерохроматином, также нет меток, экспресирующихся генов и ассоциированность с ядерной ламиной). "3" - выглядит как слабо транскрибируемая днк (похож на 1 по характеристикам типа refseq exon, но при этом небольшие участки). 

"4" - это хорошо транскрибируемая днк. часто участки после промотеров, достаточно высокий процент 
"7", "8", "9" - это энхансеры (H3K4me1 ассоциированна с энхансером, причем активным)[1], располагаются в начале генов, достаточно часто рядом с промотерами. 

"10" - 
<img width="395" alt="Снимок экрана 2022-03-26 в 21 18 03" src="https://user-images.githubusercontent.com/60537367/160252238-689b627d-2275-43f9-a508-bd1e8ea31cfc.png">





небольшой список литературы:
[1] - Sharifi-Zarchi, A., Gerovska, D., Adachi, K. et al. DNA methylation regulates discrimination of enhancers from promoters through a H3K4me1-H3K4me3 seesaw mechanism. BMC Genomics 18, 964 (2017). https://doi.org/10.1186/s12864-017-4353-7
