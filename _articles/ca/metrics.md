---
lang: ca
title: Mètriques de codi obert
description: Prendre decisions informades per ajudar a que el vostre projecte de codi obert prosperi mesurant i seguint el seu èxit.
class: metrics
toc:
  per-què-mesurar-alguna-cosa: "Per què mesurar alguna cosa?"
  descobriment: "Descobriment"
  Ús: "Ús"
  retenció: "Retenció"
  activitat-del-mantenidor: "Activitat del mantenidor"
order: 9
image: /assets/images/cards/metrics.png
related:
  - finding
  - best-practices
---

## Per què mesurar alguna cosa?

Les dades, emprades intel·ligentment, poden ajudar-te a prendre millors decisions.

Amb més informació, pots:

* Entendre com els usuaris responen a una nova característica
* Conèixer d'on provenen els nous usuaris
* Identificar i decidir si vols donar suport a un cas d'ús o a una funcionalitat
* Quantificar la popularitat del projecte
* Entendre com s'utilitza el projecte
* Guanyar diners mitjançant publicitat, donacions o subvencions

Per exemple, [Homebrew](https://github.com/Homebrew/brew/blob/bbed7246bc5c5b7acb8c1d427d10b43e090dfd39/docs/Analytics.md) va descobrir que Google Analytics els ajuda a prioritzar la feina:

> Homebrew es gratuït i està dirigit íntegrament per voluntaris en el seu temps lliure. Com a resultat, no tenim els recursos necessaris per fer estudis detallats dels usuaris d'Homebrew, per decidir sobre com dissenyar futures funcions i prioritzar la feina actual. L'anàlisi dels usuaris anònims ens permeten prioritzar les correccions i les funcions segons la manera com, on i quan la gent fa servir Homebrew.

La popularitat no ho és tot. Tothom participa en el codi obert per diferents motius. Si l'objectiu com a mantenidor de codi obert és mostrar el teu treball, donar transparència del codi o simplement ho fas per diversió, és possible que les mètriques no siguin importants.

Si _estas_ interessat a comprendre el projecte a un nivell més profund, continua llegint sobre les formes d'analitzar l'activitat del projecte.

## Descobriment

Abans que algú pugui utilitzar o contribuir en el projecte, potser necessitin conèixer abans la seva existència. Pregunta't: _està la gent trobant aquest projecte?_

![Traffic graph](/assets/images/metrics/repo_traffic_graphs_tooltip.png)

Si el projecte està allotjat a GitHub, [pots veure](https://help.github.com/articles/about-repository-graphs/#traffic) quantes persones aterren al projecte i d'on provenen. Des de la pàgina del projecte, feu clic a "Insights" i "Traffic". En aquesta pàgina, podeu veure:

* **Total pàgines visualitzades:** Us indica quantes vegades s'ha vist el projecte
* **Total visitants únics:** Us indica quantes persones han vist el projecte

* **Llocs de referència:** Us indica d'on provenen els visitants. Aquesta mètrica et pot ajudar a saber quin és el teu públic i si els esforços de promoció estan funcionant.

* **Contingut popular:** Us indica quines parts del projecte són més visitades, desglossat per vistes de pàgines i visitants únics.

[Les estrelles de GitHub](https://help.github.com/articles/about-stars/) també poden ajudar a proporcionar una mesura de popularitat. Tot i que les estrelles de GitHub no es correlacionen necessàriament amb les descàrregues i l'ús, si que mostren quantes persones estan prenent nota del treball.

Potser també vulguis [rastrejar com et descobreixen des de llocs específics](https://opensource.com/business/16/6/pirate-metrics): per exemple, Google PageRank, t'ofereix el trànsit que fa referència al lloc web del projecte o referències d'altres projectes o llocs web de codi obert.

## Ús

La gent està trobant el projecte en aquesta cosa boja i salvatge que anomenem Internet.
L'ideal seria que quan vegin el projecte, se sentissin obligades a fer alguna cosa. La segona pregunta que ens farem serà: _està la gent utilitzant aquest projecte?_

Si fas servir un gestor de paquets, com ara npm o Rubygems.org per distribuir el projecte, potser voldras rastrejar les descarregues.

Cada gestor de paquets pot utilitzar una definició lleugerament diferent de "descarrega", i les descarregues no necessàriament es correlacionen amb les instal·lacions o l'ús, però proporcionen una base de comparació. Intenta fer servir [Libraries.io](https://libraries.io/) per fer un seguiment de les estadístiques d'ús als gestors de paquets més populars.

Si el projecte está a GitHub, navega novament per la pàgina "Traffic". Pots fer servir [clone graph](https://github.com/blog/1873-clone-graphs) per veure quantes vegades s'ha clonat el teu projecte en un dia determinat, desglossat per clons totals i clons únics.
![Clone graph](/assets/images/metrics/clone_graph.png)

Si l'ús és baix en comparació amb el nombre de persones que descobreixen el projecte, cal tenir en compte dos problemes. O bé:

* El projecte no està convertint el vostre públic amb èxit, o bé
* Atreu el públic equivocat

Per exemple, si el projecte es troba a la pàgina principal de Hacker News, és probable que vegem un augment del descobriment (trànsit), però un percentatge de conversió inferior, ja que arribeu a tothom de Hacker News. Si el projecte de Ruby apareix en una conferència de Ruby, però, és més probable que vegem un alt percentatge de conversions d'un públic objectiu.

Intenta esbrinar d'on prové el teu públic i demana-li als altres informació sobre la pàgina del projecte per esbrinar a quins d'aquests dos problemes t'enfrontes.

Una vegada sàpigues que la gent està utilitzant el projecte, és possible que vulguis esbrinar què estan fent amb ell. Fan un "fork" del codi i afegeixen funcionalitats? L'estan emprant per investigació o per fer negoci?

## Retenció

La gent està trobant el projecte i l'està fent servir. La següent pregunta que et faràs serà: _està la gent contribuint al projecte?_

Mai és massa d'hora per començar a pensar en els contribuents. Sense altres persones col·laborant, es corre el risc que el projecte sigui _popular_ (moltes persones l'utilitzen) però no _recolzat_ (no hi ha prou temps per mantenir el projecte i satisfer la demanda).

La retenció també requereix una [entrada de nous contribuents](http://blog.abigailcabunoc.com/increasing-developer-engagement-at-mozilla-science-learning-advocacy#contributor-pathways_2), ja que aquests poden, en algun moment, passar a fer altres coses.

Alguns exemples de mètriques de la comunitat que voleu fer seguiment regularment inclouen:

* **Total de commits dels contribuents i nombre per contribuent:** Us indica quants contribuents teniu i qui és més o menys actiu. A GitHub, podeu veure això a "Insights" -> "Contributors". De moment, aquest gràfic només compta amb els contribuents que han fet commits a la branca per defecte del repositori.

![Contributor graph](/assets/images/metrics/repo_contributors_specific_graph.png)

* **Contribuents nous, ocasionals i repetits:** us permet fer un seguiment de si rebeu nous contribuents i si tornen. (Els contribuents ocasionals són contribuents amb un baix nombre de commits, ja sigui un commit, menys de cinc o els que siguin.) Sense nous contribuents, la comunitat del projecte pot quedar estancada.

* **Nombre de issues obertes i pull requests oberts:** Si aquestes xifres són massa elevades, és possible que necessitis ajuda per triar issues i revisar el codi.

* **Nombre de issues _obertes_ i pull requests _oberts_ :** Issues obertes vol dir que algú es preocupa pel projecte quan obre una issue. Si aquesta xifra augmenta en el temps, suggereix que la gent està interessada en el projecte.

* **Tipus de contribucions:** Per exemple, commits, correcció d'errors ortogràfics o bugs, o comentant un problema.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/arfon?s=180" class="pquote-avatar" alt="avatar">
  El codi obert és més que un codi. Els projectes de codi obert d'èxit inclouen codi i contribucions documentades, així com converses en relació a aquests canvis.
  <p markdown="1" class="pquote-credit">
— @arfon, ["The Shape of Open Source"](https://github.com/blog/2195-the-shape-of-open-source)
  </p>
</aside>

## Activitat del mantenidor

Per acabar, voldràs tancar el cercle assegurant que els mantenidors del projecte poden controlar el volum d'aportacions rebudes. L'última pregunta que voldràs preguntar és: _estic/estem preparat/s per respondre a la comunitat?_

Els mantenidors no responsables esdevenen un coll d'ampolla per als projectes de codi obert. Si algú envia una contribució i no rep cap notícia d'un mantenidor, és possible que se senti desanimat i marxi.

[Una investigació de Mozilla](https://docs.google.com/presentation/d/1hsJLv1ieSqtXBzd5YZusY-mB8e1VJzaeOmh8Q4VeMio/edit#slide=id.g43d857af8_0177) suggereix que la capacitat de resposta del mantenidor és un factor crític per fomentar les contribucions repetides.

Pensa en la possibilitat de fer un seguiment del temps que trigues (tu o un altre mantenidor) a respondre a les contribucions, ja sigui una issue o un pull request. La resposta no requereix l'adopció de mesures. Pot ser tan simple com dir: _"Gràcies per la vostra aportació. Ho revisaré durant la setmana que ve."_

També pots mesurar el temps que trigues a moure't entre etapes del procés de contribució, com ara:

* Temps mitjà que una issue roman oberta
* Si les issues es tanquen per PRs
* Si les issues obsolets es tanquen
* Temps mitjà per combinar un pull request

## Fes servir 📊 per aprendre sobre les persones

La comprensió de les mètriques t'ajudarà a crear un projecte de codi obert actiu i creixent. Fins i tot si no feu el seguiment de totes les mètriques d'un tauler, utilitzeu el marc anterior per centrar la vostra atenció en el tipus de comportament que us ajudarà a millorar el vostre projecte.
