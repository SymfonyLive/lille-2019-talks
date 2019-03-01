# [Symfony Live - Lille 2019](http://lille2019.live.symfony.com/) talks

- All talks are in **french**.

## Keynote

<dl>
  <dt>Description</dt>
  <dd>Keynote</dd>
</dl>

[Slides](https://speakerdeck.com/fabpot/2-new-symfony-components-httpclient-and-mime)  
~~Video~~

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

## Organiser et optimiser une CI complète

<dl>
  <dt>Description</dt>
  <dd>Retour d'expérience sur la mise en place d'une CI sur un projet comprenant 2 APIs et 2 applications ReactJS.

Nous en profiterons pour aborder sur la manière dont la CI a évolué au fil des différentes problématiques :

Rendre les tests end-to-end indépendants
Diviser ses tests pour mieux régner
Optimiser le chargement des fixtures
S'authentifier dans un test end-to-end
Gérer les latences des API dans un test end-to-end
Gérer l'asynchrone avec l'arrivée dans de RabbitMQ et ElasticSearch dans le projet
Optimiser sa stack Docker</dd>
</dl>

~~Slides~~  
~~Video~~

By [Hubert Lenoir](https://connect.symfony.com/profile/hubert_lenoir)  
![github](icon/github.png) [@Jean-Beru](https://github.com/Jean-Beru)  
![twitter](icon/twitter.png) [@jean_beru](https://twitter.com/jean_beru)

---

## Découvrir React et Redux avec Symfony et Webpack Encore

<dl>
  <dt>Description</dt>
  <dd>Webpack, Babel, TypeScript, React, Redux, React-Router... Autant de technologies parfois floues, mais dont on parle beaucoup. En 2019, les applications Web sont plus complexes qu'elles ne l'ont jamais été. Découvrons ensemble et par l'exemple comment mettre en place React, Redux et React-Router dans une application Symfony avec Webpack Encore.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Titouan Galopin](https://connect.symfony.com/profile/tgalopin)  
![github](icon/github.png) [@tgalopin](https://github.com/tgalopin)  
![twitter](icon/twitter.png) [@titouangalopin](https://twitter.com/titouangalopin)

---

## Mercure : des UIs toujours synchronisées avec la BDD

<dl>
  <dt>Description</dt>
  <dd>Et si l’UI vos sites web ou vos apps mobiles se mettaitent à jour en temps réel dès qu’une donnée affichée (prix, disponibilités, commentaires…) est modifiée dans le système de persistence ? Mercure permet aux serveurs de "pousser" des mises à jour en temps réel à tous types de clients.

Mercure est auto-découvrable, conçu dès le départ pour être utilisé avec des API hypermedia ou GraphQL, dispose d’un mécanisme d’autorisation qui permet de ne publier certaines mises jour qu’à certains clients autorisés, permet aux clients de se reconnecter automatiquement s'ils perdent puis retrouvent une connection, ré-envoie les messages qui se seraient perdus.

Après avoir découvert le protocole, verrons comment :

installer un serveur Mercure
découvrir le serveur côté client
s’abonner à des mises à jour
publier des mises à jour avec Symfony et API Platform (qui disposent déjà du support officiel du protocole)
mettre à jour des apps React avec les données envoyées par Mercure</dd>
</dl>

[Slides](https://www.slideshare.net/coopTilleuls/official-push-and-realtime-capabilities-for-symfony-and-api-platform-mercure-protocol)  
~~Video~~

By [Kévin Dunglas](https://connect.symfony.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)

---

## Les meilleurs bundles et outils pour vos applications Symfony

<dl>
  <dt>Description</dt>
  <dd>Il existe un large choix de bundles et d'outils permettant de d'implémenter rapidement un besoin fonctionnel ou technique. Cependant, certains bundles sont plus souples, plus rapides et plus simples à prendre en main, ce qui permet de gagner en temps dans le développement d'une feature. Tout au long de mon expérience, j'ai eu l'occasion de travailler sur des projets de natures différentes, et de recenser les besoins les plus fréquents dans une application en Symfony suivant différents points: débug, performance, gestion des mails, gestion des queues, géocodage, indexation, tests fonctionnels automatisés, qualité du code... Cette conférence permettra de détailler ces différents points avec des exemples pour illustrer.
</dd>
</dl>

~~Slides~~  
~~Video~~

By [Danielle KAYUMBI BONKOTO](https://connect.symfony.com/profile/hoddan)  
![github](icon/github.png) [@dkwavetech](https://github.com/dkwavetech)  
![twitter](icon/twitter.png) [@danielleKayumbi](https://twitter.com/danielleKayumbi)

---

## API Platform ce n'est bon qu'à faire un POC. FAUX !

<dl>
  <dt>Description</dt>
  <dd>La première chose qui est mise en avant avec API Platform c'est la capacité de faire du développement rapide d'application. C'est vrai. Ça ne signifie pas pour autant qu'il est impossible de réaliser une application complexe avec une séparation de la couche métier et de l'API publique. Voyons ensemble les mécanismes avancés d'API Platform et les outils qui en feront votre framework API en PHP.
</dd>
</dl>

[Slides](https://speakerdeck.com/gregoirehebert/lecon-numero-139-api-platform-ce-nest-bon-qua-faire-un-poc-faux)  
~~Video~~  
[Code](https://github.com/KeepMEATable/api)

By [Grégoire Hébert](https://connect.symfony.com/profile/gregoirehebert)  
![github](icon/github.png) [@GregoireHebert](https://github.com/GregoireHebert)  
![twitter](icon/twitter.png) [@gheb_dev](https://twitter.com/gheb_dev)

---

## Doctrine en dehors des sentiers battus

<dl>
  <dt>Description</dt>
  <dd>L'ORM Doctrine offre beaucoup plus de flexibilité qu'il n'y paraît. Dans cette présentation, nous allons nous intéresser à son fonctionnement interne et à ses fonctionnalités moins connues, pour découvrir comment mieux l'utiliser. Au programme, évènements et listeners, filtres, tracking policy, mais aussi des astuces sur des architectures possibles pour son code... Ne soyez pas effrayés, et attachez vos ceintures!</dd>
</dl>

~~Slides~~  
~~Video~~

By [Romaric Drigon](https://connect.symfony.com/profile/romaricdrigon)  
![github](icon/github.png) [@romaricdrigon](https://github.com/romaricdrigon)  
![twitter](icon/twitter.png) [@romaricdrigon](https://twitter.com/romaricdrigon)

---

## Top 5 des raisons d'utiliser le serveur web local de Symfony. La 6e va vous étonner !

<dl>
  <dt>Description</dt>
  <dd>Découvrez toutes les raisons d'utiliser le serveur web de la nouvelle ligne de command Symfony. Améliorez votre expérience de dev grâce à : sa simplicité, des logs user-friendly, le support de différentes versions de PHP, des noms de domaines personnalisables
du HTTPS en local configuré automatiquement. À ne manquer sous aucun prétexte !</dd>
</dl>

~~Slides~~  
~~Video~~

By [Kevin Verschaeve](https://connect.symfony.com/profile/keversc)  
![github](icon/github.png) [@kevin-verschaeve](https://github.com/kevin-verschaeve)  
![twitter](icon/twitter.png) [@keversc](https://twitter.com/keversc)
