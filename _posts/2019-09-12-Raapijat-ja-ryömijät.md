---
layout: post
title: Raapijat ja ryömijät
---

# Teknologiademo 2 #

Toteutetaan web-ryömijä (engl. crawler), joka kerää Web-sivulta tietoja dokumentin HTML-rakennetta hyödyntäen. Ensimmäisessä esimerkissä haetaan Finnkinon ohjelmistossa olevat elokuvat ja ohjaajat. Palauttakaa mieliin ennen koodiklinikkaa, miten HTML/CSS-elementit toimivat.

## Esimerkki 1 ##

__Esimerkkikoodi löytyy [täältä](https://github.com/jodatut/2018/blob/master/koodiesimerkit/raapija/crawler.py).__ Laajempia ohjeistuksia löytyy BeautifulSoupin [dokumentaatiosta](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) tai esimerkiksi [BeautifulSoup-oppaasta](https://www.dataquest.io/blog/web-scraping-beautifulsoup/).


## Esimerkki 2

Tarkastellaan vielä API-ohjelmointia vaihtoehtoisena keinona datan keräämiseen. (API-ohjelmointi on osa esitietona JODA:lle toimivaa Ohjelmallinen sisällönhallinta -opintojaksoa, mutta meidän on syytä käsitellä se erikseen.)

* [Lue yksi twiitti](https://github.com/jukkahuhtamaki/pcm-demo/blob/master/twitter-api/simple_read.py) REST-rajapinnasta
* [Datavirran tallennus](https://github.com/HYTE-research/hyte-twitter-collector) Streaming-rajapinnan avulla
