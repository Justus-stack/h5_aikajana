# Harjoitus 5

## a) Asenna 10 suosikkiohjelmaasi saltilla.

selailin internettiä ja löysin [sivun](https://linuxhint.com/100_best_ubuntu_apps/), jossa listattiin 100 kevyttä ohjelmaa, joista päätin valitsin kymmenen.

Valitsin ladattaviksi ohjemlmiksi Gimp, Synaptic, Skype, Qalculate, GnuCash, Converseen, Sublime Text, Dropbox, Filezilla ja speedcrunch

Tein /srv/salt tilan myapps, johon tein init.sls tiedoston, johon tein seuraavan rakenteen.

  myapps:
    pkg.installed:
      pkgs:
        -

tila toimi halutulla tavalla.

![kuva1](/images/kuva1.png)

## b) Lisää Microsoftin pakettivarasto ja asenna Visual Studio Code.



## c) Säädä jotain ohjelmaa ja etsi sen muuttamat tiedostot aikajanasta. Tee sitten tästä oma Saltin tila.

Päätin säätää apache2 asetuksia. 
