---
#QUESTO È LO YAML, QUI CI SONO TUTTE LE IMPOSTAZIONI IMPLICITE DEL POST
#(puoi iniziare a scrivere il tuo post dalla riga 37 in poi)

title: "{{ replace .Name "-" " " | title }}"    #Non toccare se non necessario
                                                #Se devi cambiare nome è meglio
                                                #rifare il post.

date: {{ .Date }}   #Non toccare (a meno che non vuoi
                    #rimettere a posto la data, ma occhio a
                    #scriverla bene). Se metti una data che
                    #deve ancora venire il post verrà pubblicato
                    #non prima della data indicata.

draft: false    #Metti 'true' al posto di 'false' per
                #farlo diventare una bozza.

tags: ["", ""]  #Qui ci andrebbero i tag, tipo gli hashtag.
                #Se non li usi cancella la riga. Se ne usi solo uno, cancella
                #virgola e virgolette successive.

series: [""]    #Qui ci va la serie, la tipologia di
                #prodotto. Se non le usi cancella la riga.
                #Metti le maiuscole.

categories: [""]    #Qui la categoria. Se non la usi cancella la riga.
                    #Metti le maiuscole.

img: "img/"     #Qui ci va il nome dell'immagine (con il 
                #.jpg o .png) che devi mettere in /static/img/...

toc: false      #Lacia così, a meno che non vuoi un sommario a fine post
                #(Magari per i post molto lunghi?)

summary: ""     #Qui il sommario, la scritta che compare 
                #solo come sottotitolo nel blog.
                #Metti le maiuscole.
---
