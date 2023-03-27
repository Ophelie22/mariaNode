# mariaNode
I s'agit d'une mini application de compteur afin de simulmer l'appel à une base de donnée MariaDB et le retour d'un Back et d'un Front.
Cette application est surtout utile pour avoir un point de départ avec Docker.

Pour lancer le projet il faut le cloner après avoir préaleblement installé doker sur son poste.
 Taper la commande :
 
docker compose -f docker-compose.dev.yml up 

Et se connecter sur adminer en localhost sur l'adresse :8080:8080.
lez front est visible sur le port 3000 et le back sur le meme port mais suivi du /api/count
