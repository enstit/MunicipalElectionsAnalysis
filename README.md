# 🗳 Udine municipal elections 2023

On the 2<sup>nd</sup> and 3<sup>rd</sup> of April 2023, the five-year local municipal election took place in my hometown [Udine](https://it.wikipedia.org/wiki/Udine).\
This is an excellent opportunity to practice some data analysis, since results data are publicly accessible [on the web service](https://elezioni.regione.fvg.it/consultazioni/ELZ_COM/2023-04-02/udine) provided by the Friuli-Venezia Giulia region.

## Turnout

The first statistic that immediately comes to the eye is that of (low) turnout.\
Of the 80,650 total possible voters, only 43,499 (53.94%) went to the polls on the two voting days.\
In addition, a slight superiority of female voters over male voters can be noted.
    
![Turnout](./images/output_3_0.png)
    
This is a widespread trend nationwide, as demonstrated by the CISE (Centro Italiano Studi Elettorali) [on this article](https://cise.luiss.it/cise/2022/09/27/fuga-dalle-urne-affluenza-mai-cosi-bassa-nella-storia-della-repubblica/).\
Political forces, regardless of political position, will have to question themselves with respect to this fact, and implement actions to bring citizens closer to political life.

## Voting results

We come, then, to the voting results.\
What was voted for is the renewal of the city council, and the election of the new mayor. In order to be elected, a candidate must obtain an absolute majority of the votes (50% of votes +1). This means that, since as we have seen a total of 43,499 people voted, a candidate must obtain at least 21,750 votes to be elected as mayor.\
Four challengers competed for that office:

* **Alberto Felice De Toni**, supported by the lists "Partito Democratico", "De Toni Sindaco", "Alleanza Verdi e Sinistra" and "Azione - Italia Viva - Renew Europe";
* **Ivano Marchiol**, supported by the lists "Movimento 5 Stelle", "Spazio Udine - Ivano Marchiol sindaco" and "Udine Città Futura";
* **Pietro Fontanini**, supported by the lists "Forza Italia", "Fratelli D'Italia con Giorgia Meloni", "Identità Civica", "Lega FVG per Salvini Premier", "Lista Civica Fontanini Sindaco" and "Unione di Centro";
* and **Stefano Salmè**, only supported by the "Liberi Elettori - Io amo Udine" list.

Voting allowed for one mayor, one mayor and one list associate, or one mayor, one list associate and a maximum of two preferences (of opposite sex).

The results are shown in the following image:

![Voting results](./images/output_5_0.png)
    
As you can immediately see, none of the four candidates got an absolute majority of the votes. This means that, in a couple of weeks, voters will be called again to decide the new mayor between the two candidates with the best results in this round (**Alberto Felice De Toni** with a total of 39.70%, and **Pietro Fontanini** with 46.25% of preferences).

## Most voted lists

We pass to analyze now the ranking for the most voted lists during this election. About the first six lists of this ranking, three are associated with the mayor candidate Alberto Felice De Toni, and the other three with the mayor candidate Pietro Fontanini. None of the most popular lists are associated with any of the other two candidates Ivano Marchiol and Stefano Salmè.
   
![Most voted lists](./images/output_7_0.png)

In particular, the first two lists "Partito Democratico" and "Fratelli d'Italia con Giorgia Meloni" reflect the national scenario of the most popular political parties at the moment. Worth noting, the civic list supporting Alberto Felice De Toni collected more than 12% of total consents for who voted for any list, and the number of people that voted for any of the two candidates without specifying any list is almost the same for both Alberto Felice De Toni (3,547) and Pietro Fontanini (3,565).
