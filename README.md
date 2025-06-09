# Fuzzy Matching with SAS Proc SQL
* [Summary](#summary)
* [Zip file directory](#zip-file-directory)

## Summary
- **Author:** Grace Barnhill (adapted from material by Mark Jordan)
- **Date:** 6/11/25
- **Audience:** Research Triangle SAS Users Group

In this presentation, you'll learn several techniques you can use for fuzzy matching data values that aren't strictly identical but represent the same entity. Functions discussed in this presentation include: 
- [SOUNDEX](https://documentation.sas.com/doc/en/pgmsascdc/9.4_3.5/lefunctionsref/n1i9a3o4kciemhn1kpgutl20e4i0.htm) (Base SAS)
- [SPEDIS](https://documentation.sas.com/doc/en/pgmsascdc/9.4_3.5/lefunctionsref/p0vmuxh8ljfn7on164nsgvmdrc5d.htm) (Base SAS)
- [COMPGED](https://documentation.sas.com/doc/en/pgmsascdc/9.4_3.5/lefunctionsref/p1r4l9jwgatggtn1ko81fyjys4s7.htm) (Base SAS)
- [COMPLEV](https://documentation.sas.com/doc/en/pgmsascdc/9.4_3.5/lefunctionsref/n0l41pdemybegln1oetsh4cctdap.htm) (Base SAS)
- [DQMATCH](https://documentation.sas.com/doc/en/dqcdc/default/dqclref/p09nffezbjyj4on11oblz77aq1x6.htm) (SAS Data Quality/SAS Viya)

## Zip file directory
```
├── fuzzy_matching_demo
    ├── fuzzy
    │   ├── data
    │   |   ├── catlovers.sas7bdat
    │   |   ├── catlovers2.sas7bdat
    │   |   ├── crossref.sas7bdat
    │   |   ├── customers.sas7bdat
    │   |   ├── customers2.sas7bdat
    │   |   ├── mailinglist.sas7bdat
    │   |   ├── notprospects.sas7bdat
    │   |   ├── prospects.sas7bdat
    │   |   ├── sourcedata.sas7bdat
    │   |   └── supporting_code
    │   |       ├── cre8data.sas
    │   |       ├── create_crossref_data.sas
    │   |       ├── create_customers_catlovers.sas
    │   |       ├── create_customers2_catlovers2.sas
    │   |       ├── create_mailinglist.sas
    │   |       └── create_source_and_prospects.sas
    │   ├── demos
    │   |   ├── Fuzzy Matching - 1 - Why I need it.sas
    │   |   ├── Fuzzy Matching - 2 - SOUNDEX.sas
    │   |   ├── Fuzzy Matching - 3 - SPEDIS.sas
    │   |   ├── Fuzzy Matching - 4 - COMPLEV.sas
    │   |   ├── Fuzzy Matching - 5 - COMPGED.sas
    │   |   ├── Fuzzy Matching - 6 - Complex Problems DQ Solution.sas
    │   |   └── Fuzzy Matching - Extra - PROC DQMATCH.sas
    │   └── libnames.sas
    └── Fuzzy Matching with SAS PROC SQL.pdf
```
