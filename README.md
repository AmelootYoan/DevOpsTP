# Compte-Rendu du projet de DevOps
# Étudiants : 
#        JACQUET Virgile
#        AMELOOT Yoan

# Ce qui a été fait : 

Nous avons développé un site internet mettant en valeur les qualités culinaires françaises aux travers de la charcuterie et plus présisément du saucisson.
Nous avons dockerisé un site en php utilisant une base de données SQL.

# Ce qui n'a pas été fait :

La partie "Kubernetes" n'a pas été traitée.

# Problèmes :

Nous avons rencontré un problème concernant le driver de PDO, nous n'avons donc pas réussi à lier notre base de données SQl au site php.

# Lancement du Docker :

    $ docker-compose up -d --build

--> Ensuite, dans votre navigateur, entrez l'adresse : 

    localhost:8100