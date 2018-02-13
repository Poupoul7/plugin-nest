Le plugin Nest permet de piloter le thermostat Nest et de récupérer les
informations du Nest Protect.

== Plugin configuration

Une fois le plugin installé, il vous faut renseigner vos informations de
connexion Nest :

-   **Nom d’utilisateur** : votre nom d’utilisateur Nest (souvent c’est
    votre adresse mail)

-   **Mot de passe** : mot de passe de votre compte Nest

-   **Synchroniser** : permet de synchroniser Jeedom avec votre compte
    Nest pour découvrir automatiquement vos équipements Nest. A faire
    après avoir sauvegardé les paramètres précedent.

Equipment configuration
=============================

La configuration des équipements Nest est accessible à partir du menu
plugin puis communication :

You can find here the full configuration of your device :

-   **Nom de l’équipement Nest** : nom de votre équipement Nest

-   **Parent Object** : means the parent object the equipment depend
    equipment

-   **Enable**: makes your equipment active

-   **Visible**: makes it visible on the dashboard

-   **Category**: categories of equipment (it may belong to
    plusieurs catégories)

Sur la gauche vous retrouvez :

-   **Type** : le type de votre Nest

-   **ID** : l’ID de votre équipement chez Nest

-   **IP** : l’IP de votre équipement Nest

-   **MAC** : l’adresse MAC de votre équipement Nest

-   **Batterie** : la batterie (en mV)

-   **Santé** : santé de votre Nest (0 ⇒ OK, 1 ⇒ NOK (pas OK))

-   **Remplacer le** : date de remplacement des piles

-   **Dernière mise à jour** : date de dernière mise à jour des info
    (sur un Protect c’est une fois toutes les 24h)

-   **Dernier test** : date de dernier test (Protect seulement)

En dessous vous retrouvez la liste des commandes :

-   le nom affiché sur le dashboard

-   historiser : permet d’historiser la donnée

-   configuration avancée (petites roues crantées) : permet d’afficher
    la configuration avancée de la commande (méthode
    d’historisation, widget…​)

-   Test: test the command

-   supprimer (signe -) : permet de supprimer la commande

