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
  what-does-my-companys-legal-team-need-to-know: "What does my company’s legal team need to know?"
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
* **Do you want your project to appeal to large businesses?** A large business will likely want an express patent license from all contributors. In this case, [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) has you (and them) covered.
* **Do you want your project to appeal to contributors who do not want their contributions to be used in closed source software?** [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) or (if they also do not wish to contribute to closed source services) [AGPLv3](https://choosealicense.com/licenses/agpl-3.0/) will go over well.

Your **company** may have specific licensing requirements for its open source projects. For example, it may require a permissive license so that the company can use your project in the company's closed source product. Or your company may require a strong copyleft license and an additional contributor agreement (see below) so that only your company, and nobody else, can use your project in closed source software. Or your company may have certain needs related to standards, social responsibility, or transparency, any of which could require a particular licensing strategy. Talk to your [company's legal department](#what-does-my-companys-legal-team-need-to-know).

When you create a new project on GitHub, you are given the option to select a license. Including one of the licenses mentioned above will make your GitHub project open source. If you'd like to see other options, check out [choosealicense.com](https://choosealicense.com) to find the right license for your project, even if it [isn't software](https://choosealicense.com/non-software/).

## What if I want to change the license of my project?

Most projects never need to change licenses. But occasionally circumstances change.

For example, as your project grows it adds dependencies or users, or your company changes strategies, any of which could require or want a different license. Also, if you neglected to license your project from the start, adding a license is effectively the same as changing licenses. There are three fundamental things to consider when adding or changing a your project's license:

**It's complicated.** Determining license compatibility and compliance and who holds copyright can get complicated and confusing very quickly. Switching to a new but compatible license for new releases and contributions is different from relicensing all existing contributions. Involve your legal team the first hint of any desire to change licenses. Even if you have or can obtain permission from your project's copyright holders for a license change, consider the impact of the change on your project's other users and contributors. Think of a license change as a "governance event" for your project that will more likely go smoothly with clear communications and consultation with your project's stakeholders. All the more reason to choose and use an appropriate license for your project from its inception!

**Your project's existing license.** If your project's existing license is compatible with the license you want to change to, you could just start using the new license. That's because if license A is compatible with license B, you'll comply with the terms of A while complying with the terms of B (but not necessarily vice versa). So if you're currently using a permissive license (e.g., MIT), you could change to a license with more conditions, so long as you retain a copy of the MIT license and any associated copyright notices (i.e., continue to comply with the MIT license's minimal conditions). But if your current license is not permissive (e.g., copyleft, or you don't have a license) and you aren't the sole copyright holder, you couldn't just change your project's license to MIT. Essentially, with a permissive license the project's copyright holders have given permission in advance to change licenses.

**Your project's existing copyright holders.** If you're the sole contributor to your project then either you or your company is the project's sole copyright holder. You can add or change to whatever license you or your company wants to. Otherwise there may be other copyright holders that you need agreement from in order to change licenses. Who are they? People who have commits in your project is a good place to start. But in some cases copyright will be held by those people's employers. In some cases people will have only made minimal contributions, but there's no hard and fast rule that contributions under some number of lines of code are not subject to copyright. What to do? It depends. For a relatively small and young project, it may be feasible to get all existing contributors to agree to a license change in an issue or pull request. For large and long-lived projects, you may have to seek out many contributors and even their heirs. Mozilla took years (2001-2006) to relicense Firefox, Thunderbird, and related software.

Alternatively, you can have contributors agree in advance (via an additional contributor agreement -- see below) to certain license changes under certain conditions, beyond those allowed by your existing open source license. This shifts the complexity of changing licenses a bit. You'll need more help from your lawyers up front, and you'll still want to clearly communicate with your project's stakeholders when executing a license change.

## Does my project need an additional contributor agreement?

Probably not. For the vast majority of open source projects, an open source license implicitly serves as both the inbound (from contributors) and outbound (to other contributors and users) license. If your project is on GitHub, the GitHub Terms of Service make "inbound=outbound" the [explicit default](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license).

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
  Letting out the IP associated with a patch builds the employee's knowledge base and reputation. It shows that the company is invested in the development of that employee and creates a sense of empowerment and autonomy. All of these benefits also lead to higher morale and better employee retention.
  <p markdown="1" class="pquote-credit">
— @vanl, ["A Model IP and Open Source Contribution Policy"](https://processmechanics.com/2015/07/22/a-model-ip-and-open-source-contribution-policy/)
  </p>
</aside>

* **What to release:** [(Almost) everything?](http://tom.preston-werner.com/2011/11/22/open-source-everything.html) If your legal team understands and is invested in your company's open source strategy, they'll be best able to help rather than hinder your efforts.
* **Compliance:** Even if your company doesn't release any open source projects, it uses others' open source software. [Awareness and process](https://www.linux.com/blog/why-companies-use-open-source-need-compliance-program) can prevent headaches, product delays, and lawsuits.

<aside markdown="1" class="pquote">
  Organizations must have a license and compliance strategy in place that fits both \["permissive" and "copyleft"\] categories. This begins with keeping a record of the licensing terms that apply to the open source software you’re using — including subcomponents and dependencies.
  <p markdown="1" class="pquote-credit">
— Heather Meeker, ["Open Source Software: Compliance Basics And Best Practices"](https://techcrunch.com/2012/12/14/open-source-software-compliance-basics-and-best-practices/)
  </p>
</aside>

* **Patents:** Your company may wish to join the [Open Invention Network](https://www.openinventionnetwork.com/), a shared defensive patent pool to protect members' use of major open source projects, or explore other [alternative patent licensing](https://www.eff.org/document/hacking-patent-system-2016).
* **Governança:** Especially if and when it makes sense to move a project to a [legal entity outside of the company](../leadership-and-governance/#do-i-need-a-legal-entity-to-support-my-project).
