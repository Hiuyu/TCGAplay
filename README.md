# TCGAplay

Motivation: The Cancer Genome Atlas (TCGA, https://cancergenome.nih.gov/) provides us with an enormous collection of data sets, not only spanning a large number of cancers but also a large number of experimental platforms. 

## Cancers Selected for Study
TCGA has chosen cancers for study based on specific criteria that include:
- Poor prognosis and overall public health impact
- Availability of human tumor and matched-normal tissue samples that meet TCGA standards for patient consent, quality and quantity

Below is a list of cancers that have been selected for study based on the criteria outlined above. The TCGA program has collected the necessary quality and quantity of samples for these cancers to move them into the TCGA project pipeline. Scheduling for sequencing and characterization for these cancers will be dependent on the capacity of the project pipeline. To view TCGA's clinical data forms, please visit the Biospecimen Core Resource's website (http://www.nationwidechildrens.org/biospecimen-core-resource-clinical-data-forms).

TCGA is no longer accepting additional samples for characterization. 
Analysis is underway in the following Analysis Working Groups (AWGs):
- 1 Cervical cancer，宫颈癌
- 2 Cholangiocarcinoma，胆管癌
- 3 Esophageal carcinoma，食管癌
- 4 Liver hepatocellular carcinoma，肝细胞癌
- 5 Mesothelioma，间皮瘤
- 6 Pancreatic ductal adenocarcinoma，胰腺导管腺癌
- 7 Paraganglioma & Pheochromocytoma，副神经节瘤&成嗜铬细胞瘤
- 8 Sarcoma，肉瘤
- 9 Testicular germ cell cancer，睾丸癌
- 10 Thymoma，胸腺瘤
- 11 Uterine carcinosarcoma，子宫肉瘤
- 12 Uveal melanoma，葡萄膜黑色素瘤

(*Copy from TCGA official website @ 2016-10-25*)

## more than TCGA

The National Cancer Institute’s (**NCI’s**) **Genomic Data Commons** (GDC) is a data sharing platform that promotes precision medicine in oncology. It is not just a database or a tool; it is an expandable knowledge network supporting the import and standardization of genomic and clinical data from cancer research programs.

The GDC contains NCI-generated data from some of the largest and most comprehensive cancer genomic datasets, including The Cancer Genome Atlas (**TCGA**) and Therapeutically Applicable Research to Generate Effective Therapies (**TARGET**). For the first time, these datasets have been harmonized using a common set of bioinformatics pipelines, so that the data can be directly compared.

As a growing knowledge system for cancer, the GDC also enables researchers to submit data, and harmonizes these data for import into the GDC. As more researchers add clinical and genomic data to the GDC, it will become an even more powerful tool for making discoveries about the molecular basis of cancer that may lead to better care for patients.

(*cp from GDC website @ 2016-10-25*)


## Contents
- before you start
- access to data
- preview of data
- re-analysis of data
- integration of data from multiple platforms
- xxx

## before you start



## access to data

Localization is the 1st step to re-analysis of the data. You can do this by **GDC data transfer tool** or **TCGAbiolinks**. See *preview of data* section.

### GDC data transfer tool

See https://gdc.cancer.gov/access-data/gdc-data-transfer-tool.

### TCGAbiolinks

see https://bioconductor.org/packages/devel/bioc/vignettes/TCGAbiolinks/inst/doc/tcgaBiolinks.html#updates.

### installation episode

Befor I go further, the installation of both softwares got into trouble:
- nothing happened after double-click the .exe of GDC tool
- for TCGAbiolinks, biocLite() didn't meet the latest version, but old version which cannot link to GDC data portal. Installation by localized binary source code got into a trouble of which i've no idea.  (*2016-10-15*)

## preview of data

You can preview the datasets by GDC data portal or TCGAbiolinks (updated version, supported by Bioconductor).
- GDC data portal, https://gdc-portal.nci.nih.gov/
- TCGAbiolinks, https://bioconductor.org/packages/devel/bioc/vignettes/TCGAbiolinks/inst/doc/tcgaBiolinks.html#updates

## re-analysis of data



## integration of data from different platforms


## other you might need


