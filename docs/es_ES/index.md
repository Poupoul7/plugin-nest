Le plugin Nest permet de piloter le thermostat Nest et de récupérer les
informations du Nest Protect.

> **IMPORTANT**
>
>Il n'y a pas d'API pour le Nest E en europe. Ce plugin ne permet donc pas de piloter un thermostat Nest E en europe.

> **IMPORTANT**
>
> Il n'y a pas de remonté en temps réel (juste une synchronisation toute les 15min), ce plugin ne peut donc etre utilisé pour avoir une alerte en temps réel en cas d'incendie (nest protect)

configuración del plugin
=======================

Une fois le plugin installé, il vous faut renseigner vos informations de
connexion Nest :

-   **Nom d’utilisateur** : votre nom d’utilisateur Nest (souvent c’est
    votre adresse mail)

-   **Mot de passe** : mot de passe de votre compte Nest

-   **Synchroniser** : permet de synchroniser Jeedom avec votre compte
    Nest pour découvrir automatiquement vos équipements Nest. A faire
    après avoir sauvegardé les paramètres précedent.

Configuración del dispositivo
=============================

La configuration des équipements Nest est accessible à partir du menu
plugin puis communication :

Aquí encontrará toda la configuración de su dispositivo:

-   **Nom de l’équipement Nest** : nom de votre équipement Nest

-   **Objeto padre** : especifica el objeto padre al que pertenece
    equipo

-   ** ** Activar: para que su equipo activo

-   Visible ** **: hace visible en el tablero de instrumentos

-   ** ** Categoría: categorías de equipos (que pueden pertenecer a
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

A continuación encontrará la lista de ordenes :

-   le nom affiché sur le dashboard

-   historiser : permet d’historiser la donnée

-   configuration avancée (petites roues crantées) : permet d’afficher
    la configuration avancée de la commande (méthode
    d’historisation, widget…​)

-   Prueba: prueba el comando

-   supprimer (signe -) : permet de supprimer la commande


