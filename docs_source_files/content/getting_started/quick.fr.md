---
title: "Tour rapide"
weight: 1
---

Selenium n'est pas juste un outil ou une API
mais est composé de nombreux outils.

## WebDriver

Si vous débutez dans l'automatisation de test de site web _desktop_ 
vous allez utiliser les APIs WebDriver. _[WebDriver]({{< ref "/webdriver/_index.md" >}})_ utilise 
les APIs d'automatisation fournies par les distributeurs de navigateur 
pour les contrôler et exécuter les tests. 
C'est comme si un utilisateur réel utilisait le navigateur. 
Puisque WebDriver n'a pas besoin que ses APIs soient compilées avec le code de l'application testée,
il est non intrusif par nature. Ainsi vous testez exactement l'application qui sera en production.

## IDE

_[IDE](https://selenium.dev/selenium-ide)_ (Integrated Development Environment) 
est l'outil que vous utilisez pour développer vos cas de test Selenium. Il s'agit d'un Chrome facile à utiliser
et l'extension Firefox est généralement le moyen le plus efficace de développer des 
cas de test. Il enregistre pour vous les actions des utilisateurs dans le navigateur, en utilisant
les commandes Selenium existantes, avec des paramètres définis par le contexte de
cet élément. Ce n'est pas seulement un gain de temps, mais aussi un excellent moyen
d'apprentissage de la syntaxe du script Selenium.


## Grid

Selenium Grid vous permet d'exécuter des cas de test sur différentes machines de différentes plateformes.
Le contrôle du déclenchement des cas de test est en local, et quand les tests sont déclenchés, ils sont automatiquement exécutés sur la partie distante.

Après le développement de tests WebDriver, vous pourriez avoir besoin d'exécuter les tests sur des combinaisons de multiples navigateurs et de systèmes d'exploitations.
C'est ici qu'intervient _[Grid]({{< ref "/grid/_index.md" >}})_ .
