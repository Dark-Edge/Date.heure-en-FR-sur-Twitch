# Date.heure-en-FR-sur-Twitch
Permets en utilisant la source web browser (navigateur web) d'afficher la date et l'heure en FR
Les fichiers HTML sont executé par OBS sur la source brother Web et donc le code permets de faire afficher la date / heure et de l'actualiser en temps réel.

Je ne suis pas sur de mettre a jour les fichiers mais je laisse la méthode et le code libre d'exploitation
Vous pouvez choisir d'afficher la date seukement, l'heure seulement ou les deux vu que j'ai scindé le code sur 2 parties avec 1 fichier qui renvoie chaque fonction date ou heure

La date est au format "Jour J Mois Date" et les dates au formats :

- 00:00 pour le fichier 1.0
- 0h0 pour le fichier 2.0

Voici le process en images sur OBS : 

-selection de source navigateur Web

![image](https://github.com/Dark-Edge/Date.heure-en-FR-sur-Twitch/assets/6528375/61d6b77b-9e14-48c7-9191-89956069711a)

-Modification de l'option de source pour fichier local, on récupère ensuite le fichier

![image](https://github.com/Dark-Edge/Date.heure-en-FR-sur-Twitch/assets/6528375/54ff661c-8068-47c4-b766-3943ea175714)

-Modification du rafraichissement lors de scene active

![image](https://github.com/Dark-Edge/Date.heure-en-FR-sur-Twitch/assets/6528375/de28f477-91d0-46b4-944c-ba8f92cab80a)

-Validation des paramètres apperçu dans la fenêtre

![image](https://github.com/Dark-Edge/Date.heure-en-FR-sur-Twitch/assets/6528375/cda56785-0293-4dac-98ee-1310299dbe2f)


Problèmes connus : 

- Les formats sont midifiable même si il faut connaître un minimum mais pour l'heure j'ai laissé la première version car le 2e fichier n'affiche pas systématiquement les 2 digits
