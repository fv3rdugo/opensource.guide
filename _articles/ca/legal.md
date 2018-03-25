---
lang: ca
title: Aspectes legals del codi obert
description: Tot el què t'has preguntat sobre la part legal del codi obert.
class: legal
toc:
  per-qu&egrave;-la -gent-es-preocupa-tant-sobre-els-aspectes-legals-del-codi-obert: "Per què la gent es preocupa tant sobre els aspectes legals del codi obert?"
  s&oacute;n-publics-els-projectes-de-codi-obert-de-github: "Són publics els projectes de codi obert de Github?"
  dona'm-un-resum-sobre-el-que-necessito-per-protegir-el-meu-projecte: "Dona'm un resum sobre el que necessito per protegir el meu projecte"
  which-open-source-license-is-appropriate-for-my-project: "Which open source license is appropriate for my project?"
  what-if-i-want-to-change-the-license-of-my-project: "What if I want to change the license of my project?"
  does-my-project-need-an-additional-contributor-agreement: "Does my project need an additional contributor agreement?"
  què-ha-de-saber-l'equip-jurídic-de-la-meva-empresa: "Què ha de saber l'equip jurídic de la meva empresa?"
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

La teva **empresa** pot tenir requisits de llicència específics per als seus projectes de codi obert. Per exemple, és possible que requereixi una llicència permisiva perquè l'empresa pugui utilitzar el teu projecte en el producte d'origen tancat de l'empresa. O la teva empresa pot requerir una llicència copyleft forta i un acord de col·laborador addicional (veure més abaix) de manera que només la teva empresa, i ningú més, pot utilitzar el teu projecte en programari de codi tancat. O la seva empresa pot tenir certes necessitats relacionades amb estàndards, responsabilitat social o transparència, qualsevol de les quals podria requerir una estratègia de concessió de llicències particular. Parleu amb el [vostre departament legal de la empresa](#què-ha-de-saber-l'equip-jurídic-de-la-meva-empresa).

Quan crees un nou projecte en GitHub, se't dóna l'opció de seleccionar una llicència. Incloure una de les llicències esmentades anteriorment farà que el projecte GitHub sigui de codi obert. Si voleu veure altres opcions, consulteu [choosealicense.com](https://choosealicense.com) per trobar la llicència adequada per al teu projecte, fins i tot si [no és programari](https://choosealicense.com/non-software/).

## Què passa si vull canviar la llicència del meu projecte?

La majoria dels projectes no necessiten mai canviar les llicències. Però de vegades les circumstàncies canvien.

Per exemple, a mesura que el teu projecte creix, afegeix dependències o usuaris, o la vostra empresa canvia d'estratègies, alguna de les quals podria requerir o voler una llicència diferent. A més, si heu oblidat llicenciar el teu projecte des del principi, afegir una llicència és el mateix que canviar les llicències. Hi ha tres coses fonamentals a tenir en compte a l'hora d'afegir o canviar la llicència del teu projecte:

**És complicat.** Determinar la compatibilitat i el compliment de la llicència i qui té drets d'autor pot arribar a ser complicat i confús molt ràpidament. Si canvieu a una nova llicència compatible per als nous llançaments i les contribucions, és diferent de tornar a llicenciar totes les contribucions existents. Involucri al seu equip legal davant de qualsevol desig de canviar les llicències. Fins i tot si teniu o podeu obtenir el permís dels titulars de drets d'autor del projecte per obtenir un canvi de llicència, consideri l'impacte del canvi en els altres usuaris i col·laboradors del teu projecte. Penseu en un canvi de llicència com a "esdeveniment de governança" per al teu projecte, que probablement funcionarà sense problemes amb comunicacions i consultes clares amb les parts interessades del teu projecte. Més raons per triar i utilitzar una llicència adequada per al teu projecte des de bon començament!.

**La llicència existent del projecte.** Si la llicència existent del teu projecte és compatible amb la llicència que voleu canviar, podreu començar a utilitzar la nova llicència. Això és degut a que si la llicència A és compatible amb la llicència B, compliu els termes d'A mentre compleix els termes de B (però no necessàriament a l'inrevés). Per tant, si actualment estàs utilitzant una llicència permissiva (per exemple, MIT), podríeu canviar a una llicència amb més condicions, sempre que conserveu una còpia de la llicència MIT i els avisos de drets d'autor associats (és a dir, continueu complint amb les condicions mínimes de la llicència MIT). Però si la teva llicència actual no és permissiva (p. Ex., Copyleft o no teniu una llicència) i no sou l'únic titular dels drets d'autor, no podreu canviar la llicència del teu projecte a MIT. Essencialment, amb una llicència permissiva, els titulars dels drets d'autor del projecte han permès prèviament canviar les llicències.

**Els titulars dels drets d'autor del teu projecte.** Si ets l'únic contribuent del teu projecte, ja siguis tu o la teva empresa, ets l'únic titular del copyright del projecte. Pots afegir o canviar qualsevol llicència que vulguis tu o la teva empresa. En cas contrari, pot haver altres titulars de drets d'autor amb qui necessiteu arribar a un acord per canviar les llicències. Qui són ells? Les persones que han contribuït en el teu projecte són un bon lloc per començar. Però en alguns casos els drets d'autor seran propietat de l'empresa on treballen aquestes persones. En alguns casos, les persones només haurien fet contribucions mínimes, però no hi ha cap regla ràpida i ferma que estableixi quines contribucions sobre algunes línies de codi no estan subjectes a drets d'autor. Què fer? Depèn. Per a un projecte relativament petit i jove, pot ser factible aconseguir que tots els col·laboradors existents acceptin un canvi de llicència en una issue o un pull request. Per a projectes grans i de llarga durada, és possible que hagueu de buscar molts col·laboradors i fins i tot els seus hereus. Mozilla va trigar anys (2001-2006) per poder canviar la llicència de Firefox, Thunderbird i programari relacionat.

Com a alternativa, pots tenir col·laboradors que estiguin d'acord amb anterioritat (a través d'un acord de col·laborador addicional -- veure a continuació) a certes modificacions de llicències en determinades condicions, més enllà de les permeses per la vostra llicència de codi obert existent. Això canvia una mica la complexitat del canvi de llicències. Necessitaràs més ajuda dels teus advocats al capdavant, i encara hauràs de comunicar-te clarament amb les persones interessades del teu projecte quan executeu un canvi de llicència.

## El meu projecte necessita un acord de col·laborador addicional?

Probablement no. Per a la gran majoria de projectes de codi obert, una llicència de codi obert implícitament serveix com a llicència d'entrada (de contribuents) i de sortida (a altres col·laboradors i usuaris). Si el teu projecte està en GitHub, les condicions del servei de GitHub fan que "entrant=sortint" sigui el [explícit per defecte](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license).

An additional contributor agreement -- often called a Contributor License Agreement (CLA) -- can create administrative work for project maintainers. How much work an agreement adds depends on the project and implementation. A simple agreement might require that contributors confirm, with a click, that they have the rights necessary to contribute under the project open source license. A more complicated agreement might require legal review and sign-off from contributors' employers.

Also, by adding "paperwork" that some believe is unnecessary, hard to understand, or unfair (when the agreement recipient gets more rights than contributors or the public do via the project's open source license), an additional contributor agreement may be perceived as unfriendly to the project's community.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/bcantrill?s=180" class="pquote-avatar" alt="avatar">
    We have eliminated the CLA for Node.js. Doing this lowers the barrier to entry for Node.js contributors thereby broadening the contributor base.
  <p markdown="1" class="pquote-credit">
— @bcantrill, ["Broadening Node.js Contributions"](https://www.joyent.com/blog/broadening-node-js-contributions)
  </p>
</aside>

Some situations where you may want to consider an additional contributor agreement for your project include:

* Your lawyers want all contributors to expressly accept (_sign_, online or offline) contribution terms, perhaps because they feel the open source license itself is not enough (even though it is!). If this is the only concern, a contributor agreement that affirms the project's open source license should be enough. The [jQuery Individual Contributor License Agreement](https://contribute.jquery.org/CLA/) is a good example of a lightweight additional contributor agreement. For some projects, a [Developer Certificate of Origin](https://github.com/probot/dco) can be an alternative.
* Your project uses an open source license that does not include an express patent grant (such as MIT), and you need a patent grant from all contributors, some of whom may work for companies with large patent portfolios that could be used to target you or the project's other contributors and users. The [Apache Individual Contributor License Agreement](https://www.apache.org/licenses/icla.pdf) is a commonly used additional contributor agreement that has a patent grant mirroring the one found in the Apache License 2.0.
* Your project is under a copyleft license, but you also need to distribute a proprietary version of the project. You'll need every contributor to assign copyright to you or grant you (but not the public) a permissive license. The [MongoDB Contributor Agreement](https://www.mongodb.com/legal/contributor-agreement) is an example this type of agreement.
* You think your project might need to change licenses over its lifetime and want contributors to agree in advance to such changes.

If you do need to use an additional contributor agreement with your project, consider using an integration such as [CLA assistant](https://github.com/cla-assistant/cla-assistant) to minimize contributor distraction.

## What does my company's legal team need to know?

If you're releasing an open source project as a company employee, first, your legal team should know that you're open sourcing a project.

For better or worse, consider letting them know even if it's a personal project. You probably have an "employee IP agreement" with your company that gives them some control of your projects, especially if they are at all related to the company's business or you use any company resources to develop the project. Your company _should_ easily give you permission, and maybe already has through an employee-friendly IP agreement or a company policy. If not, you can negotiate (for example, explain that your project serves the company's professional learning and development objectives for you), or avoid working on your project until you find a better company.

**If you're open sourcing a project for your company,** then definitely let them know. Your legal team probably already has policies for what open source license (and maybe additional contributor agreement) to use based on the company's business requirements and expertise around ensuring your project complies with the licenses of its dependencies. If not, you and they are in luck! Your legal team should be eager to work with you to figure this stuff out. Some things to think about:

* **Third party material:** Does your project have dependencies created by others or otherwise include or use others' code? If these are open source, you'll need to comply with the materials' open source licenses. That starts with choosing a license that works with the third party open source licenses (see above). If your project modifies or distributes third party open source material, then your legal team will also want to know that you're meeting other conditions of the third party open source licenses such as retaining copyright notices. If your project uses others' code that doesn't have an open source license, you'll probably have to ask the third party maintainers to [add an open source license](https://choosealicense.com/no-license/#for-users), and if you can't get one, stop using their code in your project.

* **Trade secrets:** Consider whether there is anything in the project that the company does not want to make available to the general public. If so, you could open source the rest of your project, after extracting the material you want to keep private.

* **Patents:** Is your company applying for a patent of which open sourcing your project would constitute [public disclosure](https://en.wikipedia.org/wiki/Public_disclosure)? Sadly, you might be asked to wait (or maybe the company will reconsider the wisdom of the application). If you're expecting contributions to your project from employees of companies with large patent portfolios, your legal team may want you to use a license with an express patent grant from contributors (such as Apache 2.0 or GPLv3), or an additional contributor agreement (see above).

* **Trademarks:** Double check that your project's name [does not conflict with any existing trademarks](../starting-a-project/#avoiding-name-conflicts). If you use your own company trademarks in the project, check that it does not cause any conflicts. [FOSSmarks](http://fossmarks.org/) is a practical guide to understanding trademarks in the context of free and open source projects.

* **Privacy:** Does your project collect data on users? "Phone home" to company servers? Your legal team can help you comply with company policies and external regulations.

If you're releasing your company's first open source project, the above is more than enough to get through (but don't worry, most projects shouldn't raise any major concerns).

Longer term, your legal team can do more to help the company get more from its involvement in open source, and stay safe:

* **Employee contribution policies:** Consider developing a corporate policy that specifies how your employees contribute to open source projects. A clear policy will reduce confusion among your employees and help them contribute to open source projects in the company's best interest, whether as part of their jobs or in their free time. A good example is Rackspace's [Model IP and Open Source Contribution Policy](https://processmechanics.com/2015/07/22/a-model-ip-and-open-source-contribution-policy/).

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
