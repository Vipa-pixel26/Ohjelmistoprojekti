#IDEOINTI
Tämä on pythonilla toteutettu tietovisa, jonka tavoitteena on testata käyttäjän tietämystä maiden pääkaupungeista.
Ohjelma valitsee viisi satunnaista maata ennalta määritellystä listasta ja kysyy käyttäjältä kunkin maan pääkaupunkia. Ohjelma sekoittaa kysymysjärjestyksen, jolloin kysymykset ovat joka kerralla erilaiset. 
Lopussa ohjelma ilmoittaa käyttäjälle, kuinka monta vastausta hän sai oikein.

#TOTEUTUS
Ohjelma on toteutettu käyttäen kolmea keskeistä rakennetta:
1. Pääkaupungit: Kaikki maat ja niiden pääkaupungit on talletettu yhteen "sanakirjaan", jossa maa on avain ja pääkaupunki on arvo.
2. Maiden sekoittaminen: random.shuffle() -funktiota käytetään sanakirjan maista luodun listan sekoittamiseen.
3. Kysymykset: Ohjelma käyttää for-silmukkaa käydessään läpi sekoitettua listaa, jotta jokainen maa käsitellään vain kerran. Silmukan sisällä input()-funktiota käytetään keräämään vastaus ja if/else-lauseilla tarkastetaan, onko vastaus sama, kuin sanakirjasta haettu oikea arvo. .lower() varmistaa, että pelaaja saa pisteen, vaikka vastaus olisi kirjoitettu isoilla kirjaimilla.
   
#KÄYNNISTYSOHJE
Ohjelman suorittamiseen tarvitset tietokoneen, johon on asennettu Python 3.

Kopioi tämä linkki 'https://github.com/Vipa-pixel26/Ohjelmistoprojekti.git' ja kloonaa se Visual Studio Coden Welcome sivun Clone Git Repository... kohtaan ja aja ohjelma.

Videotallenne ohjelman esittelystä: https://youtu.be/NnOsx999sX0




