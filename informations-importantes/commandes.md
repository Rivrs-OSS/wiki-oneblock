# 📑 Commandes

{% hint style="info" %}
`[...]` Signifie que le paramètre est obligatoire

`<...>` Signifie que vous pouvez mettre une chaine de caractères avec des espaces

`{...}` Signifie que le paramètre est optionnel
{% endhint %}

### <mark style="color:yellow;">Commandes de Base</mark> <a href="#commandes-de-base" id="commandes-de-base"></a>

`/spawn` : téléporte au spawn

`/hub` : téléporte au hub

`/codex` : ouvre les warps du spawn

`/reglement` : renvoie vers le règlement du serveur

`/wiki` : affiche toutes les informations nécessaires pour jouer sur le serveur

`/discord` : renvoie vers le serveur Discord

`/profil {pseudo}` : affiche le profil d'un joueur

`/box` : téléporte sur la box

`/jobs` : ouvre l'interface des job

`/rangs` : ouvre l'interface des rangs

`/pw` : ouvre l'interface des warps des joueurs

`/pets` : affiche le menu des companions

`/boutique` : ouvre la boutique de gemmes

`/shop` : ouvre le shop

`/ah` : ouvre l'hôtel des ventes

`/fly` : active/désactive le vol

### ONEBLOCK <a href="#box" id="box"></a>

`/ob help {1-7}` : affiche les commandes disponibles concernant les box

`/ob menu` : ouvre le menu de la box

`/ob missions` : ouvre le menu des quêtes communes aux membres pour agrandir la taille de la boxe avec plusieurs niveaux

`/ob create [nom]` : crée une box

`/ob disband` : supprime la box (disponible uniquement pour le chef)

`/ob leave` : quitte la box

`/ob invite [pseudo]` : invite un joueur à rejoindre la box

`/ob accept [pseudo/nom de l’île]` : accepte une invitation

`/ob bank` : ouvre l'interface de la banque

`/ob bank logs` : affiche les logs de la banque

`/ob deposit [somme]` : dépose de l’argent dans la banque

`/ob withdraw [somme]` : retire de l’argent de la banque

`/ob ban [pseudo]` : bannit un joueur de la box

`/ob unban [pseudo]` : débannit un joueur de la box

`/ob expel [pseudo]` : expulse un joueur présent sur la box mais pas membre de la box

`/ob kick [pseudo]` : kick un membre de la box

`/ob toggle border` : active ou désactive les bordures de la box

`/ob border [couleur]` : change la couleur des bordures de la box (personnel)

`/ob open` : ouvre la box au public

`/ob close` : ferme la box au public

`/ob coop [pseudo]` : ajoute un joueur en tant que coopérateur sur la box

`/ob uncoop [pseudo]` : retire un coopérateur de la box

`/ob coops` : ouvre le menu des coopérateurs

`/ob promote [pseudo]` : promeut le rôle d’un membre de la box

`/ob demote [pseudo]` : rétrograde le rôle d’un membre de la box

`/ob setrole [pseudo] [rôle]` : change le rôle d’un membre de la box

`/ob transfer [pseudo]` : transfère le lead de la box à un autre membre

`/ob counts {pseudo/nom de l’île}` : affiche le compteur de blocs de la box

`/ob team {pseudo/nom de l’île}` : affiche des informations sur les membres d’une box

`/ob info {pseudo/nom de l’île}` : affiche des informations sur une box

`/ob name [nom]` : change le nom de la box

`/ob upgrades` : affiche les améliorations de la box

`/ob top` : ouvre le menu du classement des box

`/ob permissions` : modifie les permissions générales de la box

`/ob permissions [pseudo]` : modifie les permissions d’un joueur sur la box

`/ob settings` : ouvre le menu des paramètres de la box

`/ob setgo` : change la position de téléportation de la box

`/ob tc` : active le chat de la box

`/ob visitors` : ouvre le menu des visiteurs

`/ob biome` : ouvre l'interface des biomes disponibles dans la box

### Jobs <a href="#jobs" id="jobs"></a>

`/jobs join [métier]` : rejoint un métier

`/jobs leave [métier]` : quitte un métier

`/jobs info [métier]` : affiche toutes les informations concernant un job

`/jobs bonus [métier]` : affiche les bonus actifs sur un job

`/jobs claim` : délivre les récompenses de paliers de jobs (faire attention à avoir de la place dans votre inventaire)

`/jobs stats {pseudo}` : affiche l'avancée globale d'un joueur

`/jobs notify` : active/désactive les notifications de jobs

### Warps <a href="#warps" id="warps"></a>

`/pw set [nom]` : définit un warp sur votre emplacement actuel

`/pw reset [nom]` : redéfinit un warp

`/pw remove [nom]` : supprime un warp

`/pw rename [ancien-nom] [nouveau-nom]` : renomme un warp

`/pw rate [nom] [1-5]` : note un warp

### Homes Personnels <a href="#homes-personnels" id="homes-personnels"></a>

`/home [nom]` : téléporte à un home personnel

`/sethome [nom]` : crée un home personnel sur votre emplacement actuel

`/delhome [nom]` : supprime un home personnel

### Téléportation entre Joueurs <a href="#teleportation-entre-joueurs" id="teleportation-entre-joueurs"></a>

`/tpa [pseudo]` : envoie une demande de téléportation à un autre joueur

`/tpahere [pseudo]` : propose à un autre joueur de se téléporter sur vous

`/tpacancel {pseudo}` : annule une demande de téléportation

`/tpaccept {pseudo}` : accepte une demande de téléportation

`/tpadeny {pseudo}` : refuse une demande de téléportation

### Cadenas <a href="#cadenas" id="cadenas"></a>

`/cadenas lock` : privatise un coffre (en ciblant le coffre, idem pour le reste des commandes)

`/cadenas unlock` : enlève la privatisation d'un coffre

`/cadenas add [pseudo]` : donne l'accès à un coffre à un joueur

`/cadenas remove [pseudo]` : enlève l'accès à un coffre à un joueur

`/cadenas list` : obtient la liste exhaustive des joueurs ayant accès au coffre

### Personnalisation <a href="#personnalisation" id="personnalisation"></a>

`/nick [pseudo/off]` : change le pseudo affiché dans le chat

`/glow` : ouvre l'interface du glow

`/cosmetics` : ouvre l'interface des cosmétiques

`/tags` : ouvre l'interface des icônes à mettre derrière son pseudo

`/ptime set [day/night/%tick%]` : change l'heure locale du joueur

`/pweather [clear/downfall/off]` : change la météo locale du joueur

`/parametres` : affiche les paramètres du joueur

### Companions <a href="#companions" id="companions"></a>

`/pet deactivate [nom du pet]` : retire le pet de la sélection active

`/pokedex` : affiche la liste de tous les companions présents sur le serveur

### Intéractions entre Joueurs <a href="#interactions-entre-joueurs" id="interactions-entre-joueurs"></a>

`/msg [pseudo] <message>` : envoie un message privé à un joueur

`/r <message>` : répond à votre dernier message privé

`/chattoggle` : active/désactive le chat global

`/ignore add [pseudo]` : ignore un joueur

`/ignore remove [pseudo]` : n'ignore plus un joueur

`/ignore removeAll` : n'ignore plus aucun des joueurs ignorés auparavant

`/ignore list` : liste tous les joueurs ignorés

`/trade [pseudo]` : propose un échange avec un joueur

`/trade accept` : accepte une demande d'échange

`/trade deny` : refuse une demande d'échange

`/pay [pseudo] [montant]` : donne de l'argent à un joueur

### Boutique <a href="#boutique" id="boutique"></a>

`/boutique_paliers` : affiche votre progession dans les paliers de boutique

`/premium` : affiche les informations concernant l'abonnement mensuel

`/objetsvip` : ouvre une boutique d'objets achetables avec des gemmes

### Shop <a href="#shop" id="shop"></a>

`/sell hand` : vend l'item que présent dans votre main

`/sell all` : vend l'entièreté de votre inventaire

### Hôtel des Ventes <a href="#hotel-des-ventes" id="hotel-des-ventes"></a>

`/ah sell [prix]` : met l'item en main en vente

`/ah average` : affiche le prix moyen de l'objet en main

`/ah viewmine` : affiche vos objets mis en vente

`/ah claim` : affiche vos objets à récupérer

`/ah history` : affiche votre historique de vente et d'achat

### Artisanat & Services <a href="#artisanat-and-services" id="artisanat-and-services"></a>

`/forge` : ouvre la forge

`/craft` : ouvre une table de craft

`/trash` : ouvre la poubelle

`/anvil` : ouvre une enclume

`/grindstone` : ouvre une meule

`/stonecutter` : ouvre une machine de découpe de pierre

`/smithingtable` : ouvre une table de forge

`/kits` : affiche les kits disponibles

`/condense` : condense les objets en blocs

`/ec` : ouvre l'ender chest

`/furnace` : cuit l'item dans votre main

`/furnace all` : cuit l'ensemble des items présents dans votre inventaire

`/repair` : répare l'item dans votre main

`/repair all` : répare l'ensemble des items présents dans votre inventaire

`/back` : retourne à votre dernière téléportation

`/feed` : restaure la barre de faim

`/regen` : restaure la barre de santé

`/xpbottle` : remplit des bouteilles d'XP Vanilla

`[i]` : identifie l'item en main dans le chat

### Quick Shops <a href="#quick-shops" id="quick-shops"></a>

`/qs help` : affiche toutes les commandes disponibles pour un shop joueur

`/qs create [somme]` : crée un shop joueur (en ciblant le coffre, idem pour le reste des commandes)

`/qs remove` : supprime un shop joueur

`/qs price [somme]` : change le prix d'achat/de vente d'un shop joueur

`/qs buy` : change le shop joueur en mode achat

`/qs sell` : change le shop joueur en mode vente

`/qs toggledisplay` : active/désactive l'affichage du shop joueur

`/qs staff add [nom]` : ajoute un gérant au shop joueur

`/qs staff del [nom]` : enlève un gérant au shop joueur

`/qs staff list` : affiche la liste des gérants du shop joueur

`/qs staff clear` : enlève tous les gérants du shop joueur

`/qs find [objet]` : localise le shop joueur le plus proche d'un type spécifique

### Autres Commandes <a href="#autres-commandes" id="autres-commandes"></a>

`/rewards` : ouvre l'interface des récompenses quotidiennes selon son temps de jeu

`/vote` : ouvre l'interface des récompenses de vote

`/voteclaim` : délivre les récompenses de vote

`/antiquaireshop` : ouvre l'antiquaire

`/bar` : ouvre le bar

`/fish shop` : ouvre le poissonnier

`/catalogue` : ouvre le catalogue premium du Minekea

`/hdb` : ouvre le catalogue de têtes

`/enchere` : téléporte aux enchères

`/mine` : téléporte à la mine

`/pw trophées` : téléporte à la salle des trophées

`/exploration` : téléporte au monde exploration

`/exploinfo` : ouvre le wiki du monde exploration

`/compass` : active/désactive le codex dans votre inventaire

`/classements` : affiche les différents classements

`/events` : ouvre l'interface des événements

`/collections` : ouvre l'interface des différentes collections

`/droptoggle` : active/désactive le système anti-drop d'items

`/clearlag info` : indique le temps restant avant le prochain clearlag

`/limits` : indique la limite d'items que vous pouvez poser dans votre box pour certains items

`/generateur` : affiche les différentes paliers du générateur

`/fly time` : affiche le temps de vol disponible

`/whereiam` : affiche le serveur sur lequel vous êtes actuellement

`/e` : ouvre la liste des emojis disponibles

`/sb` : active/désactive le scoreboard lors des évènements, à écrire 2 fois pour désactiver
