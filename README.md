# NFHS-5: National Family Health Survey (2019-20)

[![CC BY 4.0][cc-by-shield]][cc-by]

CSV Fact sheets for key indicators from http://rchiips.org/nfhs/.
PDF files are automatically converted and manually edited for few.
Quality checks have been minimally done. Please recheck with source before doing any analysis.

### Download

- [NFHS-5-States.csv](NFHS-5-States.csv): 22 states level data for 131 indicators
- [NFHS-5-Districts.csv](NFHS-5-Districts.csv): 341 districts from 21 states
- District level files (state-wise)
  - [NFHS-5-AN-Andaman-and-Nicobar-Island.csv](./district-level/NFHS-5-AN-Andaman-and-Nicobar-Island.csv)
  - [NFHS-5-AP-Andhra-Pradesh.csv](./district-level/NFHS-5-AP-Andhra-Pradesh.csv)
  - [NFHS-5-AS-Assam.csv](./district-level/NFHS-5-AS-Assam.csv)
  - [NFHS-5-BR-Bihar.csv](./district-level/NFHS-5-BR-Bihar.csv)
  - [NFHS-5-DD-Dadra-Nagar-Haveli-and-Daman-Diu.csv](./district-level/NFHS-5-DD-Dadra-Nagar-Haveli-and-Daman-Diu.csv)
  - [NFHS-5-GA-Goa.csv](./district-level/NFHS-5-GA-Goa.csv)
  - [NFHS-5-GJ-Gujarat.csv](./district-level/NFHS-5-GJ-Gujarat.csv)
  - [NFHS-5-HP-Himachal-Pradesh.csv](./district-level/NFHS-5-HP-Himachal-Pradesh.csv)
  - [NFHS-5-JK-Jammu-and-Kashmir.csv](./district-level/NFHS-5-JK-Jammu-and-Kashmir.csv)
  - [NFHS-5-KA-Karnataka.csv](./district-level/NFHS-5-KA-Karnataka.csv)
  - [NFHS-5-KL-Kerala.csv](./district-level/NFHS-5-KL-Kerala.csv)
  - [NFHS-5-LH-Ladakh.csv](./district-level/NFHS-5-LH-Ladakh.csv)
  - [NFHS-5-MH-Maharashtra.csv](./district-level/NFHS-5-MH-Maharashtra.csv)
  - [NFHS-5-ML-Meghalaya.csv](./district-level/NFHS-5-ML-Meghalaya.csv)
  - [NFHS-5-MN-Manipur.csv](./district-level/NFHS-5-MN-Manipur.csv)
  - [NFHS-5-MZ-Mizoram.csv](./district-level/NFHS-5-MZ-Mizoram.csv)
  - [NFHS-5-NL-Nagaland.csv](./district-level/NFHS-5-NL-Nagaland.csv)
  - [NFHS-5-SK-Sikkim.csv](./district-level/NFHS-5-SK-Sikkim.csv)
  - [NFHS-5-TG-Telangana.csv](./district-level/NFHS-5-TG-Telangana.csv)
  - [NFHS-5-TR-Tripura.csv](./district-level/NFHS-5-TR-Tripura.csv)
  - [NFHS-5-WB-West-Bengal.csv](./district-level/NFHS-5-WB-West-Bengal.csv)

### Citation

```
@misc{pratapvardhan_2020_nfhs5,
  author = {Pratap Vardhan, Bhanu K},
  title = {{Dataset for NFHS-5: National Family Health Survey (2019-20)}},
  howpublished = {\url{https://github.com/pratapvardhan/NFHS-5}},
  note = {Accessed: yyyy-mm-dd}
  year = 2020
}
```

Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---

### Issues
- NFHS-5-states.csv
    - DONE: Manually add Meghalaya's 111-131 indicators.
- DONE: Add 1 row for `Himachal Pradesh,HP,Kangra,104. Men age 15 years and above who consume alcohol (%),34.1,,,`
- DONE: Edit 1 row for `Himachal Pradesh,HP,Chamba,31. Current users ever told about side effects of current method8 (%),71.7,,Based on 25-49 unweighted cases,Based on 25-49 unweighted cases`
- DONE: GJ-Mahisagar and MH-Wardha has wrong questions order from 11 to 32.
- DONE: Few districts have extra spaces in questions. Standardize names.
- Old
  - DONE: KA, KL are showing old files on the site, pulled latest from direct URLs
  - DONE: Get [MH-Thane](https://docs.google.com/spreadsheets/d/1U6dR6x-_8mVmhsub11h3kSZuY6Cm8aBlmjybKcE3rqk/edit?usp=sharing) from sheet.

### TODO (Need help)

- Manually crowd check districts data with PDFs. Sample QA check.

### Archive
<details>
  <summary>Bhanu K helped setup manual tagging for 29 files. Click to expand.</summary>

You can manually convert one of the 29 pdf files and submit as PR/Issue. 

**[Bhanu K](https://github.com/bkamapantula)** has setup data cleaning process at: https://docs.google.com/spreadsheets/d/1U6dR6x-_8mVmhsub11h3kSZuY6Cm8aBlmjybKcE3rqk/edit?usp=sharing -- request **edit access** to contribute.
- Manually crowd check districts data with PDFs. Sample QA check.
- Manually fix 29 files. See [status.csv](status.csv).
    - [HP/Bilaspur.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/HP/Bilaspur.pdf)
    - [HP/Chamba.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/HP/Chamba.pdf)
    - [HP/Hamirpur.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/HP/Hamirpur.pdf)
    - [HP/Kangra.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/HP/Kangra.pdf)
    - [HP/Kinnaur.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/HP/Kinnaur.pdf)
    - [HP/Kullu.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/HP/Kullu.pdf)
    - [HP/Lahul and Spiti.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/HP/Lahul%20and%20Spiti.pdf)
    - [HP/Mandi.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/HP/Mandi.pdf)
    - [HP/Shimla.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/HP/Shimla.pdf)
    - [HP/Una.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/HP/Una.pdf)
    - [MH/Palghar.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/MH/Palghar.pdf)
    - [MH/Thane.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/MH/Thane.pdf)
    - [ML/East Garo Hills.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/ML/East%20Garo%20Hills.pdf)
    - [ML/East Jaintia Hills.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/ML/East%20Jaintia%20Hills.pdf)
    - [ML/North Garo Hills.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/ML/North%20Garo%20Hills.pdf)
    - [ML/South West Garo Hills.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/ML/South%20West%20Garo%20Hills.pdf)
    - [ML/South West Khasi Hills.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/ML/South%20West%20Khasi%20Hills.pdf)
    - [ML/West Jaintia Hills.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/ML/West%20Jaintia%20Hills.pdf)
    - [ML/West Khasi Hills.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/ML/West%20Khasi%20Hills.pdf)
    - [TR/Gomati.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/TR/Gomati.pdf)
    - [TR/Khowai.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/TR/Khowai.pdf)
    - [TR/North Tripura.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/TR/North%20Tripura.pdf)
    - [TR/Sepahijala.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/TR/Sepahijala.pdf)
    - [TR/South Tripura.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/TR/South%20Tripura.pdf)
    - [TR/Unakoti.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/TR/Unakoti.pdf)
    - [TR/West Tripura.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/TR/West%20Tripura.pdf)
    - [ML/West Garo Hills.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/ML/West%20Garo%20Hills.pdf)
    - [HP/Sirmaur.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/HP/Sirmaur.pdf)
    - [HP/Solan.pdf](http://rchiips.org/NFHS/NFHS-5_FCTS/HP/Solan.pdf)
</details>

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg