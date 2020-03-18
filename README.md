# SCP-277-FR_addScp
Repository pour ajouter vous même vos SCP préférés

Ici vous pouvez faire une "Pull request" avec dedans un fichier **.js** qui contient la commande.
______________

Voici un exemple:

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

> Dans le 2ème argument du ".addField()" (``.addField("1er argument", "2eme argument")``), il doit y avoir maximum 1024 caractères
> Pour revenir à la ligne, il faut, à la place d'entrer, mettre un "\n" (Exemple: ``.addField("Bla ?", "Blablabla\nBlablabla\nBlabla\n\nBlabla"``). 1 "\n" = revenir une fois à la ligne, 2 "\n" = revenir 2 fois à la ligne
> 
> Si sur le rapport de la Fondation il y a un mot en italique ou en gras (sauf dans le premier argument du ".addField()", il doit paraître en italique ou en gras dans la commande

                                       __________________________________________________         1  1 1 1 1 1 1  1 2  1  1 3 ev r r f f f f  f f f f f f f f f f f  f f f f f f f  f f f f f  f g
