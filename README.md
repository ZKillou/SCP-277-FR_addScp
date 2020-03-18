# SCP-277-FR_addScp
Repository pour ajouter vous même vos SCP préférés sur le bot SCP-277-FR

Ici vous pouvez faire une "Pull request" avec dedans un fichier **.js** qui contient la commande.
______________

Voici un exemple (il y en a un plus complet [ici](https://github.com/ZKillou/SCP-277-FR_addScp/blob/master/exemple.js)):

```js
if(message.content === prefix + "lenumeroduscp"){
	let embed = new Discord.RichEmbed()
	.setColor('0x000000')
	.setFooter(ftr, authpdp)
	.setThumbnail("https://cdn.discordapp.com/avatars/568437925453234176/7817bef4754c41be03e31f16d47802ff.png?size=2048")
	.addField("Info", "**Titre:** blablabla\n**Objet #:** SCP-XXX-XX\n(**Niveau de menace:** Couleur)\n**Classe:** blabla")
	.addField("Procédures de Confinement Spéciales", "blablabla")
	.addField("Description", "blablabla")
	.addField("Annexe num", "blablabla")
	message.channel.send(embed)
}
```
_____________

Attention,

> Dans le 2ème argument du ".addField()" (``.addField("1er argument", "2eme argument")``), il doit y avoir maximum 1024 caractères. ([Voici un compteur de caractère en ligne](https://compteurdelettres.com/))
> 
> De plus, un embed ne doit pas dépasser 6000 caractères (mais ça je m'en occupe tout seul)
> 
> Pour revenir à la ligne, il faut, à la place d'entrer, mettre un "\n" (Exemple: ``.addField("Bla ?", "Blablabla\nBlablabla\nBlabla\n\nBlabla"``). 1 "\n" = revenir une fois à la ligne, 2 "\n" = revenir 2 fois à la ligne
> 
> Si sur le rapport de la Fondation il y a un mot en italique ou en gras (sauf dans le premier argument du ".addField()", il doit paraître en italique ou en gras dans la commande (Tu ne sais pas comment faire ? [Clique là](https://support.discordapp.com/hc/fr/articles/210298617-Bases-de-la-mise-en-forme-de-texte-Markdown-mise-en-forme-du-chat-gras-italique-soulign%C3%A9-)
> 
> S'il y a une sorte de carré sur le rapport (comme ça ![carré fondation](https://cdn.discordapp.com/attachments/505784854017736705/689833516779044931/Screenshot_20200318-145117_Chrome.jpg) tu dois faire un bloc de code de plusieurs lignes sans mettre de caractère en gras ou en italique
> 
> C'est à peu près tout... Je pense.

_____________

En cas de problème, vous pouvez rejoindre mon [serveur Discord](https://discord.gg/NyUukwA) et n'hésite pas à [ajouter](https://discordapp.com/oauth2/authorize?client_id=568437925453234176&scope=bot&permissions=8) le bot sur votre serveur et [voter](https://top.gg/bot/568437925453234176/vote) pour lui !
