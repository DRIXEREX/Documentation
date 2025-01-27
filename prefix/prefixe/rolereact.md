---
description: >-
  Un rolereact permet à vos membres d'obtenir eux-mêmes un rôle en cliquant sur
  la réaction, le bouton ou le sélecteur d'un message de DraftBot.
---

# RoleReact

## Créer le rolereact <a href="#create" id="create"></a>

Pour créer un `rolereact`, vous avez le choix entre trois méthodes :

{% hint style="warning" %}
Peu importe la méthode que vous choisissez, le rolereact devra être sur un message de **DraftBot**.
{% endhint %}

* **Simple message :** `say [message]` \
  La commande `say` permet d'envoyer un simple message Discord depuis DraftBot.

{% hint style="info" %}
Vous pourrez modifier ce message dans le futur avec la commande `say` [`[Identifiant du message]`](../../autres/recuperer-un-identifiant.md#message) ou depuis le panel web !
{% endhint %}

* **Embed automatique :** `rolereact create [Titre de l'embed]` \
  Cette solution vous permet de créer un  embed qui sera modifié lors de l'ajout ou le retrait d'un rôle dans le rolereact. À la fin de la configuration, l'embed ressemblera à cela :&#x20;

![Résultat d'un rolereact utilisant un embed automatique](<../../.gitbook/assets/image (10).png>)

* **Embed personnalisé :** `embed` ou [depuis le panel web](https://www.draftbot.fr/dashboard) dans l'onglet **Embeds** de votre serveur.\
  Cette méthode vous permet de créer un embed totalement personnalisable à votre goût.\
  Voici un exemple de cette méthode : &#x20;

![Résultat d'un rolereact utilisant un embed personalisé](<../../.gitbook/assets/image (9).png>)

## Ajouter un rôle à un rolereact <a href="#add" id="add"></a>

Pour ajouter à un rôle à un rolereact, il vous suffit d'utiliser la commande `rolereact add [Identifiant du message de DraftBot]`

{% hint style="info" %}
Besoin d'aide pour récupérer l'identifiant d'un message ? [Cliquez ici !](../../autres/recuperer-un-identifiant.md#message)
{% endhint %}

Ensuite, **DraftBot** vous demandera quel rôle doit être ajouté. Vous pouvez donner le nom du rôle ou le mentionner, les deux solutions fonctionnent.

{% hint style="danger" %}
Pour que le rolereact fonctionne, **DraftBot** doit posséder au moins un rôle qui est au-dessus du grade que vous souhaitez ajouter au rolereact.
{% endhint %}

Et pour finir, **DraftBot** vous demandera quel émoji doit être cliqué pour obtenir ce rôle, il vous suffit de l'écrire.

{% hint style="info" %}
Si vous souhaitez ajouter un autre rolereact au même message, il vous suffit de répéter la même opération.
{% endhint %}

## Supprimer un rôle à un rolereact <a href="#delete" id="delete"></a>

Pour supprimer un rôle d'un rolereact, il vous suffit d'utiliser la commande `rolereact remove [Identifiant du message de DraftBot]`

{% hint style="info" %}
Besoin d'aide pour récupérer l'identifiant d'un message ? [Cliquez ici !](../../autres/recuperer-un-identifiant.md#message)
{% endhint %}

**DraftBot** vous demandera ensuite quel émoji du rolereact doit être supprimé, indiquez-le !

{% hint style="info" %}
Si vous souhaitez supprimer un autre rolereact du même message, il vous suffit de répéter la même opération.
{% endhint %}

## Mode d'un rolereact

Vous pouvez choisir un mode pour vos rôles réactions. \
Cela vous offre la possibilité de pouvoir retirer un rôle lorsqu'un de vos membres clique sur une réaction par exemple.\
\
Vous pouvez configurer cela avec la commande `rolereact mode`.\
Après cela, DraftBot vous demandera l'identifiant du message de **DraftBot** pour le rolereact.

{% hint style="info" %}
Besoin d'aide pour récupérer l'identifiant d'un message ? [Cliquer ici !](../../autres/recuperer-un-identifiant.md#message)
{% endhint %}

Ensuite vous aurez le choix entre cinq possibilités, que vous aurez à valider en cliquant sur un des boutons en dessous du message de **DraftBot**.

![Message obtenu après avoir effectué la commande rolereact mode](<../../.gitbook/assets/Mode rolereact.png>)
