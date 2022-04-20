# HallintaH3

## A. MarkDown. Tee tämän tehtävän raportti MarkDownina. Helpointa on tehdä raportti GitHub-varastoon, jolloin md-päätteiset tiedostot muotoillaan automaattisesti. Tyhjä rivi tekee kappalejaon, risuaita ‘#’ tekee otsikon, sisennys merkitsee koodinpätkän.

Aloitetaan luomalla githubiin repository. Seuraavaksi miedän pitäisi ottaa ssh yhteys githubiin, mutta teimme sen jo tunnilla. Ssh avaimen saat luotua komennolla:
	ssh-keygen -t ed25519 -C "oma@email.com"
Seuraavaksi kloonataan repo käytössä olevalle koneelle komennolla:
	git clone git@github.com:K-Jesse/HallintaH3.git
Sitten voikin aloittaa tiedoston muokkaamisen kun ollaan saatu git toimimaan.

## B. Pull first. Tee useita muutoksia git-varastoosi. Tee muutama muutos, jossa yksi commit koskee useampaa tiedostoa. Anna hyvä kuvaukset (commit message), yksi englanninkielinen lause imperatiivissa (määräysmuodossa) "Add top level menu to Foobar synchronizer"

Tehdään tähän kansioon uusi MarkDown tiedosto nimellä testi01 ja lisätään sinne testisisältöä. Myös toki muokataan tätä tiedostoa edellä kirjatulla materiaalilla.
![Image](".\HallintaH3\git muokkaus.jpg")

## C. Kaikki kirjataan. Näytä omalla git-varastollasi esimerkit komennoista ‘git log’, ‘git diff’ ja ‘git blame’. Selitä tulokset.

Komennolla:
	git log
Saadaan tietoa kommiteista: Sieltä löytyy tekijä, aika ja kommentti mitä commitissa on tehty. (ensimmäinen kuva)
[Link](https://imgur.com/a/6hUbGWl)
	git diff


## D. Huppis! Tee tyhmä muutos gittiin, älä tee commit:tia. Tuhoa huonot muutokset ‘git reset --hard’. Huomaa, että tässä toiminnossa ei ole peruutusnappia.

## E. Formula. Tee uusi salt-tila (formula, moduli, infraa koodina). (Eli uusi tiedosto esim. /srv/salt/terontila/init.sls). Voit tehdä ihan yksinkertaisen parin funktion (pkg, file...) tilan, tai edistyneemmin asentaa ja konfiguroida minkä vain uuden ohjelman: demonin, työpöytäohjelman tai komentokehotteesta toimivan ohjelman. Käytä tarvittaessa ‘find -printf “%T+ %p\n”|sort’ löytääksesi uudet asetustiedostot.
