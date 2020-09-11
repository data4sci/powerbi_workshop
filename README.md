# powerbi_workshop
poznámky k Czechitas Workshopu 10.10.2020 @VŠB
<https://www.czechitas.cz/cs/kalendar-akci/akce/22821/?utm_source=Czechitas+Newsletter&utm_campaign=a835eb617f-czechitas+newsletter+09+2020&utm_medium=email&utm_term=0_443df25591-a835eb617f-175053417>

## TODO

* VM s instalací PostgreSQL (VŠB)
    * bez firewallu, READ kdokoliv z eduroam
    * cvičná databáze 
* CSV s cvičnými daty (toy dataset)
    * [Google Play Store](https://www.kaggle.com/lava18/google-play-store-apps)
    * (Boston house-prices](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html#sklearn.datasets.load_boston)
* dva datasety, které JOIN v Power BI?

## Prerekvizity

* instalace [Power BI Desktop](powerbi.microsoft.com) a registrace
* základy (kurz odkaz)
* účet <GitHub.com>
* účet <kaggle.com>

## Agenda

* 
* Datový sklad /datový rybník
    * denormalizovaná data VS 3. NF
    * ETL, logs (auditní záznamy)
    * Architektura
        * source systems
        * stage
        * presentation
            * datamarts
        * access tools
            * Power BI
            * Tablou
            * Google Data Studio 
    * 
* Business Intelligence / Kimball model
    * Fact Tables (konkrétní business proces, 1 řádek = událost/transakce, hodnoty (fakta) jsou aditivní!)
        * prodej
        * nákup
        * zkouška
        * ...
    * Dimensional Tables (5W), dodávají kontext FT
        * čas
        * místo
        * organizační struktura
        * produktový katalog
        * ...
        * historizace
    * Star / Snowflake
    * Změna chování rozhodovatelů na základě ... ?
    *
* Zákazník/uživatel (strategické rozhodování)
    * Jak poznáte, že se blíží problém?
    * Jak poznáte, že to co děláte, děláte dobře?
    * Podle čeho jste hodnoceni?
    * ...
    * KPI
* Čištění dat
* Transformace dat (tidy dataset)
* Datové modelování
* ML, experimenty, ...
* Data Science Team
    * Data Engineer
    * Data Analyst
    * Data Scientist
* Data katalog
* Data Governance - kdo je zodpovědný za který datový zdroj
* Code book (popis konkrétního datasetu)
* Nástroje
    * Python (+ Pandas), R
    * Markdown
    * git
    * Linux
    * CLI/shell/bash/...
    * SQL, NoSQL (Cypher)
    * 
* platformy
    * AWS
    * Google Cloud Platform 
    * Microsoft Azure
*
*
* diskuze ke každému podtématu



