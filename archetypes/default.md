---
#QUESTE È LO YAML, QUI CI SONO TUTTE LE IMPOSTAZIONI IMPLICITE DEL POST
#(puoi iniziare a scrivere il tuo post dalla riga 31 in poi)

title: "{{ replace .Name "-" " " | title }}"    #Non toccare.

date: {{ .Date }}   #Non toccare (a meno che non vuoi
                    #rimettere a posto la data, ma occhio a
                    #scriverla bene).

draft: false    #Metti 'true' al posto di 'false' per
                #farlo diventare una bozza.

tags: ["", ""]  #Qui ci andrebbero i tag, tipo gli hashtag.
                #Se non li usi cancella la riga.

series: [""]    #Qui ci va la serie, la tipologia di
                #prodotto. Se non le usi cancella la riga.

categories: [""]    #Qui la categoria. Se non la usi cancella la riga.

img: "img/"     #Qui ci va il nome dell'immagine (con il 
                #.jpg) che devi mettere in /static/img/...

toc: false      #Lacia così, a meno che non vuoi un sommario a fine post
                #(Magari per i post molto lunghi?)

summary: ""     #Qui il sommario, la scritta che compare 
                #solo come sottotitolo nel blog
---
