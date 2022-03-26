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
<img width="478" alt="Снимок экрана 2022-03-24 в 15 00 01" src="https://user-images.githubusercontent.com/60537367/159911751-28cd4e48-6b10-4de1-8939-d14181dea377.png">






"1" предположительно более слабый промотер, так как идет более короткими кчастками после "2", также менее выражены CpG островки и TSS. "2", соответственно, активный промотер: идет в начале гена, выражены CpG островки и TSS. Также многочисленные модификации, которые ассоциированны с данными состояниями, ассоцирированы именно с промотерами. Например, H3K4me3, отвечает за низкий уровень метилирования (собственно, промотеры низкометилированные, с cpg островками)[1][2]. "3" выглядит как слабый/ неактивный промотер (маленькие участки в начале гена), возможно артефакт, часто чередуется с 4. 

"4" выглядит как слабо транскрибируемая ДНК. "5" - это гетерохроматин (наибольший процент аннотированного генома представлен гетерохроматином, также нет меток, экспресирующихся генов и ассоциированность с ядерной ламиной). "6". 

"7", "8" - это энхансеры (H3K4me1 ассоциированна с энхансером, причем активным). 

"9". "10".


небольшой список литературы:
[1] - Sharifi-Zarchi, A., Gerovska, D., Adachi, K. et al. DNA methylation regulates discrimination of enhancers from promoters through a H3K4me1-H3K4me3 seesaw mechanism. BMC Genomics 18, 964 (2017). https://doi.org/10.1186/s12864-017-4353-7
[2] - Kharchenko PV, Alekseyenko AA, Schwartz YB, et al. Comprehensive analysis of the chromatin landscape in Drosophila melanogaster. Nature. 2011;471(7339):480-485. doi:10.1038/nature09725
[3] - Farooq Z, Banday S, Pandita TK, Altaf M. The many faces of histone H3K79 methylation. Mutat Res Rev Mutat Res. 2016;768:46-52. doi:10.1016/j.mrrev.2016.03.005
