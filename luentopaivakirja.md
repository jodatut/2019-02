---
layout: default
title: Luentopäiväkirja / JODA syksyllä 2019
year: 2019-02
---

Tämä on Johdanto datatieteeseen -opintojakson syksyn 2019 toteutuskerran luentopäiväkirja.

Toteutuskerta noudattelee [syksyn 2018 toteutusta](https://jodatut.github.io/2018/luentopaivakirja/).  

<!-- Vastaisen varalle:
Toteutus noudattelee [vuoden 2018 toteutuskertaa](https://jodatut.github.io/2018/luentopaivakirja).
Alan dynaamisuudesta johtuen sisältöjä ja toteutustapaa kuitenkin kehitetään jatkuvasti.
-->

<!--
karkean
[luentosuunnitelman](https://docs.google.com/document/d/1drHb2HtmFy_Nu5iVuCtqZV6C9OjsoGMQqDrvDhV7fIc/edit?usp=sharing)
mukaisesti. -->

<!--
Totetutuskerran käytössä on
[Slack-kanava](https://join.slack.com/t/jodatut/shared_invite/enQtMzQyNzE1NzgxNDQwLTIyNmE5OGQwYWIxMjc3MjU2MDU1Mzc0NTQ0OWE3OTg4Y2I5Y2E0MDkxYTAyZjQwNTJhYTFmZGJhNDdiNzMwOTg).
Osa luennoista tallennetaan [Echo360-järjestelmällä](https://echo360.org.uk/section/c9dd83a0-b703-47e7-82fe-545ff4644e75/public).

# Luentopäiväkirja

Kaikkien aikojen ensimmäinen Johdanto datatieteeseen -toteutuskerta on päättynyt.
Katsasta seuraavaksi esimerkiksi opintojaksot [Data- ja informaatioanalytiikka](http://www.tut.fi/opinto-opas/wwwoppaat/opas2017-2018/perus/aineryhmat/Tiedonhallinta/TLO-35100.html) ja
[Introduction to Pattern Recognition and Machine Learning](http://www.tut.fi/opinto-opas/wwwoppaat/opas2017-2018/kv/aineryhmat/Signaalinkasittely/SGN-13006.html).

-->


<!--

Viimeisellä varsinaisella luentokerralla käydään läpi datan vuorovaikutteista eksploratiivista analytiikka ja luodaan tiekarttaa kohti datatuotteiden kehittämistä. Lue artikkeli [Designing and Developing Analytics-Based Data Products](https://sloanreview.mit.edu/article/designing-and-developing-analytics-based-data-products/) ja katso Jeffrey Heerin [keynote-esitys visuaalisesta analytiikasta](https://www.youtube.com/watch?v=hsfWtPH2kDg).

[Koodiklinikalla](https://jodatut.github.io/2018/Datan-visualisointi) päästään tekemään visualisointeja siihen tarkoitettujen kirjastojen avulla sekä luomaan yksinkertainen web-sovellus datan ympärille.

-->
## Luentoviikko 7: Ohjaamaton koneoppiminen

Miten ohjattu ja ohjaamaton oppiminen eroavat toisistaan?
<!-- Kuva alla versionhallinnassa: https://jodatut.github.io/2019-02/figure/unsupervised-learning-workflow.jpg -->
Ohjaamaton oppiminen (ks. [Unsupervised learning workflow](https://goo.gl/images/dCm55z)),
[ostoskorianalyysi](http://pbpython.com/market-basket-analysis.html),
[verkostoanalyysi](https://github.com/jukkahuhtamaki/demo-twitter-collector/blob/master/README.md) (ks. [Marvel social graph](https://blog.dataiku.com/2015/05/19/marvel-social-graph-analysis), [Marvel-datasetti](http://syntagmatic.github.io/exposedata/marvel/)),
ryvästäminen (ks. [k-means-clustering](https://www.datascience.com/blog/k-means-clustering), [k-means -perusteet ja scikit-learn](https://blog.floydhub.com/introduction-to-k-means-clustering-in-python-with-scikit-learn/), [ammattiprofiilit](https://twitter.com/heinihm/status/1194216183161114624)),
aihemallinnus eli [topic modeling](https://medium.com/mlreview/topic-modeling-with-scikit-learn-e80d33668730) ja sen [riskit](https://rajapinta.co/2017/07/08/varovaisuutta-aihemallinnuksen-kanssa/).

Koodiklinikalla tutustutaan [ryvästämiseen ostoskorianalyysin kautta](https://jodatut.github.io/2019-02/Ostoskorianalyysi).

## Luentoviikko 6: Harjoitustyön edistäminen

Kuudennella luentoviikolla keskitytään harjoitustyön edistämiseen.

Koodiklinikalla käydään läpi [karttavisualisoinnin toteuttaminen Plotly-palvelulla](https://jodatut.github.io/2019/Datan-visualisointi) ja esimerkkejä [datan suodattamisesta ja pyörittelystä](https://github.com/jodatut/demos-and-examples/blob/master/airbnb/tinkering-with-Airbnb-data.ipynb).

## Luentoviikko 5: Visuaalinen analytiikka

Katso ennen luentoa: [Jeffrey Heerin keynote-esitys visuaalisesta analytiikasta](https://www.youtube.com/watch?v=hsfWtPH2kDg).

[Informaation visualisoinnin vaiheet](https://jodatut.github.io/2019-02/informaation-visualisoinnin-vaiheet/), datan visualisointi ([esimerkkejä Pythonilla](https://towardsdatascience.com/5-quick-and-easy-data-visualizations-in-python-with-code-a2284bae952f),
[Plotly](https://plot.ly/python/),
[Seaborn](https://seaborn.pydata.org/),
[Seaborn-tutoriaali](https://medium.com/@neuralnets/statistical-data-visualization-series-with-python-and-seaborn-for-data-science-5a73b128851d)),
visuaalinen analytiikka ([Heerin keynote](https://www.youtube.com/watch?v=hsfWtPH2kDg)),
eksploratiivinen analytiikka ([esimerkki Pythonilla](https://towardsdatascience.com/exploratory-analysis-python-kaggle-data-b0afb6ec1788)), vuorovaikutteinen analytiikka,
datatuotteet ([Designing and Developing Analytics-Based Data Products](https://sloanreview.mit.edu/article/designing-and-developing-analytics-based-data-products/)).

Koodiklinikalla käytiin yksityiskohtaisesti läpi [Airbnb-hintaennustimen toteutusta](https://github.com/jodatut/demos-and-examples/tree/master/airbnb).

## Luentoviikko 4: Harjoitustyöhön tutustuminen

Lue ennen luentoa: [Predicting Airbnb Listing Prices with Scikit-Learn and Apache Spark](https://mapr.com/blog/predicting-airbnb-listing-prices-scikit-learn-and-apache-spark/)

Johdanto datatieteeseen -harjoitustyössä käydään läpi datatiedeprojektin keskeiset vaiheet.
Voit valita aiheen ja datalähteen vapaasti.
Saat pisteitä julkaisemalla Slackissa kuvauksen [harjoitustyön eri vaiheiden](https://jodatut.github.io/2019-02/harjoitustyo/) toteutuksesta.
Eräs vaihtoehto on Airbnb-aineiston analysointi.
Voit vaikkapa toteuttaa hintaennustimen [esimerkkianalyysiä](https://mapr.com/blog/predicting-airbnb-listing-prices-scikit-learn-and-apache-spark/) soveltamalla. Katso myös [simple-regression](https://github.com/jodatut/demos-and-examples/blob/master/simple-regression/simple-regression.ipynb) ja [exploring-gapminder](https://github.com/jodatut/demos-and-examples/blob/master/simple-regression/exploring-gapminder.ipynb).

Koodiklinikalla syvennytään [datan käsittelyyn lineaariregressiota varten](https://jodatut.github.io/2019-02/Kategoriset-muuttujat-ja-puuttuva-data).

## Luentoviikko 3: Koneoppimisen periaatteet

Lue ennen luentoa: [Näin laadullinen tieto jalostuu laskennalliseksi: piirteet sosiaalisen median analytiikassa](https://rajapinta.co/2017/10/16/nain-laadullinen-tieto-jalostuu-laskennalliseksi-piirteet-sosiaalisen-median-analytiikassa/)

Koneoppimisen työnkulku (ks. [Supervised learning workflow](https://jodatut.github.io/2019-02/figure/supervised-learning-workflow.jpg)),
sovellusesimerkki: [asiakaspoistuma-analyysi](http://www.louhia.fi/2014/08/27/asiakaspoistuma-analyysi-ja-miljoona-lisamyyntia/),
piirteiden erottaminen (ks. [esilukemisto](https://rajapinta.co/2017/10/16/nain-laadullinen-tieto-jalostuu-laskennalliseksi-piirteet-sosiaalisen-median-analytiikassa/)),
piirteiden jalostaminen (ks.
[feature engineering](https://medium.com/mindorks/what-is-feature-engineering-for-machine-learning-d8ba3158d97a)),
luokittelu Pythonilla ([step-by-step tutorial](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/)),
dataesimerkkejä (ks. [IBM Watson Community](https://dataplatform.cloud.ibm.com/community)),
dataan tutustuminen käyntiin (ks.
[explore](https://github.com/jodatut/2018/tree/master/koodiesimerkit/explore)).

Koodiklinikalla [esimerkkejä lineaariregressiosta](https://jodatut.github.io/2019-02/Lineaariregressio).


## Luentoviikko 2: Datan kerääminen ja jalostaminen

Datatiedeprosessin vaiheet ([Data Science Workflow](https://cacm.acm.org/blogs/blog-cacm/169199-data-science-workflow-overview-and-challenges/fulltext)),
kerääminen ja jalostaminen [datatieteen metrokartassa](http://nirvacana.com/thoughts/2013/07/08/becoming-a-data-scientist/),
[ETL vs. DAD](https://www.datasciencecentral.com/profiles/blogs/data-scientist-versus-data-engineer),
ryömijät ja raapijat
([Web crawler](https://en.wikipedia.org/wiki/Web_crawler),
[Web scraping](https://en.wikipedia.org/wiki/Web_scraping),
[Web Scraping in Python](https://www.analyticsvidhya.com/blog/2015/10/beginner-guide-web-scraping-beautiful-soup-python/),
[Scrapy](https://scrapy.org/),
[Scraping for journalists](https://leanpub.com/scrapingforjournalists)),
dataformaatit ja niiden ohjelmallinen käsittely,
data wrangling (ks. [DataWrangler](http://vis.stanford.edu/wrangler/)),
datan jalostaminen Pythonilla
(ks. [Pandas-toimintokooste](https://www.datacamp.com/community/blog/pandas-cheat-sheet-python)),
vrt. [OpenRefine](http://openrefine.org/).

Koodiklinikalla käsittelyssä [raapijat ja ryömijät](https://jodatut.github.io/2019-02/Raapijat-ja-ry%C3%B6mij%C3%A4t/).

## Luentoviikko 1: Johdanto aihepiiriin ja suorittaminen

Avausluento tiistaina 27. elokuuta kello 17-20 Edutechissä.
Suorittamisen käytännöt.
Mitä on datatiede
([CRISP-DM](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining),
[modern data scientist](https://www.schoolofdatascience.amsterdam/news/skills-need-become-modern-data-scientist/),
[datatieteen metrokartta](http://nirvacana.com/thoughts/2013/07/08/becoming-a-data-scientist/))?
Datatieteen työvälineet:
[Pandas](https://pandas.pydata.org/),
[scikit-learn](http://scikit-learn.org/),
[D3.js](https://d3js.org/),
[Jupyter](http://jupyter.org/).
Dataa koneeseen:
read_csv() & read_excel().
[Jupyter-koeajo](https://github.com/jodatut/2019-02/blob/master/koodiesimerkit/jupyter-demo/Koeajossa-Jupyter.ipynb).

Ensimmäisellä Koodiklinikalla käydään läpi Pandas-kirjaston perusteita sekä eri kehitysympäristöjä, ks. [Datatieteen perusteet](https://jodatut.github.io/2019-02/Datatiede-perusteet/).

<!--Liittykää myös kurssin [Slack-kanavalle](https://join.slack.com/t/jodatut/shared_invite/enQtMzIyOTk4NjI5OTM2LTU2NDUwM2I0ZmRhZmI4Y2E5OWM1NGE1MTA5NDQ5NGRhMDI3NWI0MjUxZDA5MjIxMjhmNmFlYmI5YzRjZTdmOWU).-->
