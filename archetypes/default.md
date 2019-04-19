---
title: "{{ replace .Name "-" " " | title }}"            #Non toccare
date: {{ .Date }}                                       #Non toccare (a meno che non vuoi                                                                  rimettere a posto la data, ma occhio a                                                            scriverla bene)
draft: true                                             #metti 'true' al posto di 'false' per                                                              farlo diventare una bozza
tags: ["", ""]                                          #Qui ci andrebbero i tag, tipo gli hashtag
series: [""]                                            #Qui ci va la serie, la tipologia di                                                               prodotto
categories: [""]                                        #Qui la categoria
img: "img/"                                             #Qui ci va il nome dell'immagine (con il                                                           .jpg) che devi mettere in /static/img/...
toc: false
summary: ""                                             #Qui il sommario, la scritta che compare                                                           solo come sottotitolo nel blog
---

