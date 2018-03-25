---
lang: ca
title: Aspectes legals del codi obert
description: Tot el què t'has preguntat sobre la part legal del codi obert.
class: legal
toc:
  per-què-la-gent-es-preocupa-tant-sobre-els-aspectes-legals-del-codi-obert: "Per què la gent es preocupa tant sobre els aspectes legals del codi obert?"
  els-projectes-públics-de-github-són-de-codi-obert: "Els projectes públics de GitHub són de codi obert?"
  donam-un-resum-sobre-el-que-necessito-per-protegir-el-meu-projecte: "Dona'm un resum sobre el que necessito per protegir el meu projecte"
  quina-llicència-de-codi-obert-és-lapropiada-per-al-meu-projecte: "Quina llicència de codi obert és l'apropiada per al meu projecte?"
  què-passa-si-vull-canviar-la-llicència-del-meu-projecte: "Què passa si vull canviar la llicència del meu projecte?"
  el-meu-projecte-necessita-un-acord-de-collaborador-addicional: "El meu projecte necessita un acord de col·laborador addicional?"
  què-ha-de-saber-lequip-jurídic-de-la-meva-empresa: "Què ha de saber l'equip jurídic de la meva empresa?"
order: 10
image: /assets/images/cards/legal.png
related:
  - contribute
  - leadership
---

## Comprenent les implicacions legals del codi obert

Compartir el teu treball creatiu amb el mon pot ser una experiència excitant i gratificant. Això també comporta un conjunt d'aspectes legals dels cuals t'has d'ocupar. Afortunadament, no tens que començar de zero. Nosaltres tenim cobertes les teves necessitats legals. (Abans de continuar, assegureu-vos de llegir el nostre [avís legal](/notices/).)

## Per què la gent es preocupa tant sobre els aspectes legals del codi obert?

Bona pregunta! Quan realitzeu un treball creatiu (com ara l'escritura, dibuix, o el codi), el treball es troba sota drets d'autor per defecte. Es a dir, la llei assumeix que, com a autor del teu treball, tens poder de decisió sobre el que els altres poden fer amb ell.

En general, això significa que ningú més pot utilitzar, copiar, distribuir o modificar el teu treball sense correr riscos d'embargaments, ser investigat o demandat.

El codi obert és una circumstància inusual, però, perquè l'autor espera que altres utilitzin, modifiquin i comparteixin el treball. Però degut a que el valor per defecte legal continua sent exclusiu de drets d'autor, necessiteu una llicència que estableixi explícitament aquests permisos.

Si no aplica una llicència de codi obert, tothom que contribueixi al teu projecte també es converteix en un titular de drets d'autor exclusiu del seu treball. Això significa que ningú pot utilitzar, copiar, distribuir ni modificar les seves contribucions, i aquest "ningú" t'inclou a tu.

Finalment, el teu projecte pot tenir dependències amb requisits de llicència que desconeixíeu. La comunitat del teu projecte o les polítiques de contractació també poden requerir que el teu projecte utilitzi llicències de codi obert específiques. Anem a cobrir aquestes situacions a continuació.

## Els projectes públics de GitHub són de codi obert?

Quan [creeu un projecte nou](https://help.github.com/articles/creating-a-new-repository/) a GitHub, teniu l'opció de fer el repositori **privat** o **públic**.

![Create repository](/assets/images/legal/repo-create-name.png)

**Fer el teu projecte de GitHub públic no és el mateix que llicenciar el teu projecte.** Els projectes públics estan coberts per les [Condicions del servei de GitHub](https://help.github.com/articles/github-terms-of-service/#f-copyright-and-content-ownership), que permet a altres usuaris veure i bifurcar el teu projecte, però el teu treball no conté cap permís.

Si voleu que altres persones utilitzin, distribueixin, modifiquin o facin aportacions al teu projecte, heu d'incloure una llicència de codi obert. Per exemple, ningú no pot legalment utilitzar cap part del projecte de GitHub en el seu codi, encara que sigui públic, tret que explícitament es donin drets per fer-ho.

## Dona'm un resum sobre el que necessito per protegir el meu projecte

Estas de sort, perquè avui, les llicencies de codi lliure són estàndard i fàcils d'utilitzar. Tu pots fer un copia-enganxa d'una llicència existent directament al teu projecte.

[MIT](https://choosealicense.com/licenses/mit/), [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/), i [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) són les llicencies de codi obert més populars, però també tens altres opcions per escollir. Pots trobar un text complert sobre aquestes llicencies, i instruccions d'ús en [choosealicense.com](https://choosealicense.com/).

Quant crees un nou projecte a Github, se't [demanarà afegir una llicència](https://help.github.com/articles/open-source-licensing/).

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/benbalter?s=180" class="pquote-avatar" alt="avatar">
  Una llicència estàndard serveix com aproximació per als que no tenen entrenament legal per saber amb precisió el que poden i el que no poden fer amb el programari. A no ser que sigui absolutament necessari, eviteu termes personalitzats, modificats o no estàndard, que serviran de barrera per a l'ús posterior del codi d'agència.
  <p markdown="1" class="pquote-credit">
— @benbalter, ["Everything a government attorney needs to know about open source software&nbsp;licensing"](https://ben.balter.com/2014/10/08/open-source-licensing-for-government-attorneys/)
  </p>
</aside>

## Quina llicència de codi obert és l'apropiada per al meu projecte?

Si comences des de zero, és difícil equivocar-se a l'escollir la [llicència MIT](https://choosealicense.com/licenses/mit/). És curta, molt fàcil d'entendre, i permet a qualsevol fer el que consideri, sempre i quant mantingui una còpia de la llicència, incloent-hi el teu avís de drets d'autor. Tindras la possibilitat d'alliberar el projecte sota una altre llicència si així ho necessites.

Dit d'una altre manera, triar la llicència de codi obert corresponent al teu projecte depèn dels teus objectius.

Probablement el teu projecte tingui (o tindrà) **dependències**. Per exemple, si és un projecte de codi obert de Node.js, és probable que utilitzeu llibreries del gestor de paquets de node (npm). Cadascuna de les llibreries que en depengui tindrà la seva pròpia llicència de codi obert. Si cadascuna de les seves llicències és "permissiva" (dóna permís al públic per utilitzar-la, modificar-la i compartir-la, sense cap condició per a la concessió de llicències aigües avall), podeu utilitzar qualsevol llicència que vulgueu. Les llicències permissives habituals són MIT, Apache 2.0, ISC i BSD.

D'altra banda, si alguna de les llicències de les teves dependències és "copyleft fort" (també dona el mateix permís, subjecte a la condició d'utilitzar la mateixa llicència aigües avall), el teu projecte haurà d'utilitzar la mateixa llicència. Les llicències comuns de copyleft fort inclouen GPLv2, GPLv3 i AGPLv3.

Hauries de considerar també el que les **comunitats** esperen que facis servir per contribuir al teu projecte:

* **Vols que el teu projecte sigui utilitzat com a dependència per a altres projectes?** Probablement la millor opció sigui utilitzar la llicència més popular de la teva comunitat. Per exemple, [MIT](https://choosealicense.com/licenses/mit/) ho és per les [llibreries npm](https://libraries.io/npm).
* **Voleu que el teu projecte sigui atractiu per a grans empreses?** Una gran empresa probablement voldrà una llicència de patent expressa de tots els col·laboradors. En aquest cas, [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) et te a tu (i a ells) coberts.
* **Voleu que el teu projecte atregui col·laboradors que no vulguin que les seves contribucions s'utilitzin en programari de codi tancat?** [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) o (si tampoc volen contribuir a serveis de codi tancat) [AGPLv3](https://choosealicense.com/licenses/agpl-3.0/) seria la més apropiada.

La teva **empresa** pot tenir requisits de llicència específics per als seus projectes de codi obert. Per exemple, és possible que requereixi una llicència permisiva perquè l'empresa pugui utilitzar el teu projecte en el producte d'origen tancat de l'empresa. O la teva empresa pot requerir una llicència copyleft forta i un acord de col·laborador addicional (veure més abaix) de manera que només la teva empresa, i ningú més, pot utilitzar el teu projecte en programari de codi tancat. O la seva empresa pot tenir certes necessitats relacionades amb estàndards, responsabilitat social o transparència, qualsevol de les quals podria requerir una estratègia de concessió de llicències particular. Parleu amb el [teu departament legal de la empresa](#què-ha-de-saber-l'equip-jurídic-de-la-meva-empresa).

Quan crees un nou projecte en GitHub, se't dóna l'opció de seleccionar una llicència. Incloure una de les llicències esmentades anteriorment farà que el projecte GitHub sigui de codi obert. Si voleu veure altres opcions, consulteu [choosealicense.com](https://choosealicense.com) per trobar la llicència adequada per al teu projecte, fins i tot si [no és programari](https://choosealicense.com/non-software/).

## Què passa si vull canviar la llicència del meu projecte?

La majoria dels projectes no necessiten mai canviar les llicències. Però de vegades les circumstàncies canvien.

Per exemple, a mesura que el teu projecte creix, afegeixes dependències o usuaris, o la vostra empresa canvia d'estratègies, alguna de les quals podria requerir o voler una llicència diferent. A més, si heu oblidat llicenciar el teu projecte des del principi, afegir una llicència és el mateix que canviar les llicències. Hi ha tres coses fonamentals a tenir en compte a l'hora d'afegir o canviar la llicència del teu projecte:

**És complicat.** Determinar la compatibilitat i el compliment de la llicència i qui té drets d'autor pot arribar a ser complicat i confús molt ràpidament. Si canvieu a una nova llicència compatible per als nous llançaments i les contribucions, és diferent de tornar a llicenciar totes les contribucions existents. Involucri al seu equip legal davant de qualsevol desig de canviar les llicències. Fins i tot si teniu o podeu obtenir el permís dels titulars de drets d'autor del projecte per obtenir un canvi de llicència, consideri l'impacte del canvi en els altres usuaris i col·laboradors del teu projecte. Penseu en un canvi de llicència com a "esdeveniment de governança" per al teu projecte, que probablement funcionarà sense problemes amb comunicacions i consultes clares amb les parts interessades del teu projecte. Més raons per triar i utilitzar una llicència adequada per al teu projecte des de bon començament!.

**La llicència existent del projecte.** Si la llicència existent del teu projecte és compatible amb la llicència que voleu canviar, podreu començar a utilitzar la nova llicència. Això és degut a que si la llicència A és compatible amb la llicència B, compliu els termes d'A mentre compleix els termes de B (però no necessàriament a l'inrevés). Per tant, si actualment estàs utilitzant una llicència permissiva (per exemple, MIT), podríeu canviar a una llicència amb més condicions, sempre que conserveu una còpia de la llicència MIT i els avisos de drets d'autor associats (és a dir, continueu complint amb les condicions mínimes de la llicència MIT). Però si la teva llicència actual no és permissiva (p. Ex., Copyleft o no teniu una llicència) i no sou l'únic titular dels drets d'autor, no podreu canviar la llicència del teu projecte a MIT. Essencialment, amb una llicència permissiva, els titulars dels drets d'autor del projecte han permès prèviament canviar les llicències.

**Els titulars dels drets d'autor del teu projecte.** Si ets l'únic contribuent del teu projecte, ja siguis tu o la teva empresa, ets l'únic titular del copyright del projecte. Pots afegir o canviar qualsevol llicència que vulguis tu o la teva empresa. En cas contrari, pot haver altres titulars de drets d'autor amb qui necessiteu arribar a un acord per canviar les llicències. Qui són ells? Les persones que han contribuït en el teu projecte són un bon lloc per començar. Però en alguns casos els drets d'autor seran propietat de l'empresa on treballen aquestes persones. En alguns casos, les persones només haurien fet contribucions mínimes, però no hi ha cap regla ràpida i ferma que estableixi quines contribucions sobre algunes línies de codi no estan subjectes a drets d'autor. Què fer? Depèn. Per a un projecte relativament petit i jove, pot ser factible aconseguir que tots els col·laboradors existents acceptin un canvi de llicència en una issue o un pull request. Per a projectes grans i de llarga durada, és possible que hagueu de buscar molts col·laboradors i fins i tot els seus hereus. Mozilla va trigar anys (2001-2006) per poder canviar la llicència de Firefox, Thunderbird i programari relacionat.

Com a alternativa, pots tenir col·laboradors que estiguin d'acord amb anterioritat (a través d'un acord de col·laborador addicional -- veure a continuació) a certes modificacions de llicències en determinades condicions, més enllà de les permeses per la vostra llicència de codi obert existent. Això canvia una mica la complexitat del canvi de llicències. Necessitaràs més ajuda dels teus advocats al capdavant, i encara hauràs de comunicar-te clarament amb les persones interessades del teu projecte quan executeu un canvi de llicència.

## El meu projecte necessita un acord de col·laborador addicional?

Probablement no. Per a la gran majoria de projectes de codi obert, una llicència de codi obert implícitament serveix com a llicència d'entrada (de contribuents) i de sortida (a altres col·laboradors i usuaris). Si el teu projecte està en GitHub, les condicions del servei de GitHub fan que "entrant=sortint" sigui el [explícit per defecte](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license).

Un acord de col·laborador addicional -- sovint anomenat Acord de llicència de contribuent (CLA) -- pot crear treballs administratius per als mantenidors del projecte. La quantitat de treball que un acord afegeix depèn del projecte i la implementació. Un acord simple podria requerir que els contribuents confirmin, amb un clic, que tenen els drets necessaris per a contribuir amb la llicència de codi obert del projecte. Un acord més complicat pot requerir revisió legal i aprovació dels empresaris dels contribuents.

A més, afegint "tràmits" que alguns creuen que són innecessaris, difícils d'entendre o injust (quan el destinatari de l'acord obté més drets que els contribuents o el públic ho fa a través de la llicència de codi obert del projecte), un acord de contribuent addicional es pot percebre poc amigable per la comunitat del projecte.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/bcantrill?s=180" class="pquote-avatar" alt="avatar">
    Hem eliminat el CLA per a Node.js. Fent això, es redueix la barrera d'entrada per als contribuents de Node.js, ampliant així la base de col·laboradors.
  <p markdown="1" class="pquote-credit">
— @bcantrill, ["Broadening Node.js Contributions"](https://www.joyent.com/blog/broadening-node-js-contributions)
  </p>
</aside>

Algunes de les situacions en què potser vols considerar un acord de col·laborador addicional per al teu projecte inclouen:

* Els teus advocats volen que tots els contribuents acceptin expressament (_signatura_, en línia o fora de línia) els termes de contribució, potser perquè senten que la llicència de codi obert no és suficient (encara que ho sigui!). Si aquesta és l'única preocupació, un acord de col·laborador que afirmi la llicència de codi obert del projecte hauria de ser suficient. L'[Acord de llicència de contribuïdor individual jQuery](https://contribute.jquery.org/CLA/) és un bon exemple d'un acord de contribució addicional lleuger. Per a alguns projectes, un [Certificat d'origen del desenvolupadors](https://github.com/probot/dco) pot ser una alternativa.

* El teu projecte utilitza una llicència de codi obert que no inclou una concessió de patent expressa (com ara MIT), i necessiteu una concessió de patent de tots els contribuents, alguns dels quals poden treballar per a empreses amb grans carteres de patents que podrien utilitzar-se per orientar-te o els altres col·laboradors i usuaris del projecte. EL'[Acord de llicència de contribuïdor individual d'Apache](https://www.apache.org/licenses/icla.pdf) és un acord de contribuïdor addicional que s'utilitza habitualment que té una concessió de patents que reflecteix el que es troba en la llicència Apache 2.0.
* El teu projecte està sota una llicència de copyleft, però també heu de distribuir una versió propietària del projecte. Necessitaràs que tots els contribuents t'assignin els drets d'autor o que et concedeixin (però no al públic) una llicència permissiva. L'[Acord de col·laborador de MongoDB](https://www.mongodb.com/legal/contributor-agreement) és un exemple d'aquest tipus d'acord.
* Creus que és possible que el teu projecte canviï de llicències al llarg de la seva vida i que els contribuents estiguin d'acord amb anticipació a aquests canvis.

Si necessiteu utilitzar un acord de col·laborador addicional per al teu projecte, considera utilitzar una integració com ara [assistent de CLA](https://github.com/cla-assistant/cla-assistant) per minimitzar la distracció dels contribuents.

## Què ha de saber l'equip jurídic de la meva empresa?

Si publiques un projecte de codi obert com a empleat d'una empresa, primer, el teu equip jurídic hauria de saber que vols obrir un publicar un projecte de codi obert.

Per bé o per mal, considereu fer-los saber fins i tot si és un projecte personal. Probablement tingui un "acord de Propietat Intelectual (IP) de l'empleat" amb la teva empresa que els proporcioni un control sobre els teus projectes, especialment si estan relacionats amb el negoci de la companyia o si utilitza recursos de la companyia per desenvolupar el projecte. La teva empresa _hauria_ de donar-te permís fàcilment, i potser ja ho ha fet a través d'un acord de propietat intel·lectual favorable a l'empleat o una política d'empresa. Si no, podeu negociar (per exemple, explica que el teu projecte serveix els objectius professionals de l'aprenentatge i desenvolupament professional de la teva empresa), o bé evita treballar en el teu projecte fins que trobis una empresa millor.

**Si esteu treballant en un projecte de codi obert per a la teva empresa** llavors definitivament fes-ho saber. El teu equip legal probablement ja té polítiques sobre quina és la llicència de codi obert (i potser un acord de contribuent addicional) que s'utilitzarà en funció dels requisits comercials de l'empresa i la seva experiència per garantir que el teu projecte compleixi les llicències de les seves dependències. Si no, tant tu com ells esteu de sort! El teu equip jurídic hauria d'estar ansiós per treballar amb vosaltres per esbrinar aquestes coses. Alguns aspectes a considerar:

* **Material de tercers:** El teu projecte té dependències creades per altres o incloeu o utilitza el codi d'un altre? Si es tracta de codi obert, haurà de complir les llicències de codi obert dels materials. Això comença amb l'elecció d'una llicència que funciona amb les llicències de codi obert de tercers (vegeu més amunt). Si el teu projecte modifica o distribueix material de codi obert de tercers, el teu equip legal també voldrà saber que compleix altres condicions de les llicències de codi obert de tercers, com ara retenir avisos de drets d'autor. Si el teu projecte utilitza el codi d'altres que no té una llicència de codi obert, és probable que hagueu de demanar als mantenidors de tercers que [afegeixin una llicència de codi obert](https://choosealicense.com/no-license/#for-users), i si no podeu obtenir-ne una, deixeu d'utilitzar el codi en el teu projecte.

* **Secrets comercials:** Considera si hi ha alguna cosa al projecte que l'empresa no vulgui posar a disposició del públic en general. Si és així, podríeu fer de codi obert la resta del teu projecte, després d'extreure el material que voleu mantenir privat.

* **Patents:** Esta la teva empresa sol·licitant una patent, i alliberar el teu codi font constituexi [divulgació pública](https://en.wikipedia.org/wiki/Public_disclosure)? Lamentablement, se't demanarà que esperis (o potser l'empresa reconsiderarà la saviesa de l'aplicació). Si esperes obtenir contribucions al teu projecte d'empleats d'empreses amb grans carteres de patents, és possible que el teu equip legal us demani que utilitzeu una llicència amb una concessió de patent expressa dels contribuents (com ara Apache 2.0 o GPLv3), o un acord de contribuent addicional ( Vegeu més amunt).

* **Marques comercials:** Comproveu que el nom del teu projecte [no entra en conflicte amb cap marca comercial existent](../starting-a-project/#evitant-conflictes-amb-els-noms). Si utilitzeu marques comercials pròpies de la teva empresa, comproveu que no provoqui cap conflicte. [FOSSmarks](http://fossmarks.org/) és una guia pràctica per comprendre les marques comercials en el context de projectes de codi obert i lliure.

* **Privacitat**: el teu projecte recopila dades dels usuaris? "Telèfon particular" en els servidors de la empresa? El teu equip legal us pot ajudar a complir amb les polítiques de l'empresa i amb les normatives externes.

Si publiques el primer projecte de codi obert de la teva empresa, amb tot l'exposat anteriorment és més que suficient per aconseguir-ho (però no et preocupis, la majoria dels projectes no t'haurien de plantejar cap problema important).

A més llarg termini, el teu equip legal pot fer més per ajudar a l'empresa a obtenir més de la seva participació en codi obert i mantenir-se segur:

* **Polítiques de contribucions d'empleats:** Considereu desenvolupar una política corporativa que especifiqui com els vostres empleats contribueixen a projectes de codi obert. Una política clara reduirà la confusió entre els vostres empleats i els ajudarà a contribuir amb projectes de codi obert en el millor interès de la companyia, ja sigui en el lloc de treball o en el seu temps lliure. Un bon exemple és el [Model PI i la política de contribucions de codi obert de Rackspace](https://processmechanics.com/2015/07/22/a-model-ip-and-open-source-contribution-policy/).

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/vanl?s=180" class="pquote-avatar" alt="avatar">
  Alliberar la Propietat Intel·lectual (PI) associada amb un parche, genera la base de coneixement i la reputació de l'empleat. Mostra que l'empresa inverteix en el desenvolupament d'aquest empleat i crea un sentit de empoderament i autonomia. Tots aquests beneficis també condueixen a una major moral i millor retenció dels empleats.
  <p markdown="1" class="pquote-credit">
— @vanl, ["A Model IP and Open Source Contribution Policy"](https://processmechanics.com/2015/07/22/a-model-ip-and-open-source-contribution-policy/)
  </p>
</aside>

* **Què publicar:** [(Gairebé) tot?](Http://tom.preston-werner.com/2011/11/22/open-source-everything.html) Si el teu equip legal entén i s'inverteix en l'estratègia de codi obert de la teva empresa, seran els més capaços d'ajudar-te en comptes d'obstaculitzar els teus esforços.
* **Compliment:** Fins i tot si la vostra empresa no publica cap projecte de codi obert, utilitza el programari de codi obert d'altres persones. [Coneixement i procés](https://www.linux.com/blog/why-companies-use-open-source-need-compliance-program) pot prevenir mals de cap, retards en els productes i demandes judicials.

<aside markdown="1" class="pquote">
Les organitzacions han de tenir una llicència i una estratègia de compliment que s'adapti a les categories \[ "permissiva" i "copyleft"\]. Això comença amb mantenir un registre dels termes de llicència que s'apliquen al programari de codi obert que està utilitzant, inclosos els subcomponents i les dependències.
  <p markdown="1" class="pquote-credit">
— Heather Meeker, ["Open Source Software: Compliance Basics And Best Practices"](https://techcrunch.com/2012/12/14/open-source-software-compliance-basics-and-best-practices/)
  </p>
</aside>

* **Patents:** És possible que la teva empresa vulgui unir-se a la [Xarxa d'Invenció Oberta](https://www.openinventionnetwork.com/), un conjunt de patents defensives compartides per protegir l'ús de grans projectes de codi obert pels membres o explorar altres [llicencies de patents alternatives](https://www.eff.org/document/hacking-patent-system-2016).
* **Governança:** Sobretot si té sentit moure un projecte a una [entitat legal fora de l'empresa](../leadership-and-governance/#do-i-need-a-legal-entity-to-support-my-project).
