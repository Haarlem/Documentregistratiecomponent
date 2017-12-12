Alfresco Share module

Dit project bevat de customized layout van de eigenschappen van de diverse custom node typen in Alfresco.
Tevens bevat het de layout van de 'advanced search' pagina.

Het build proces produceert een zgn .amp file (alfresco module package) en een .jar file

Beiden kunnen gebruikt worden om een deploy te realiseren.

Deploy locatie van de jar file : alfresco\modules\share

LET OP! verwijder eenmalig bij een eerst volgende deploy het bestand alfresco\tomcat\webapps\share\WEB-INF\lib\OSShareConfig-haarlem.jar

De huidige jar is van naam veranderd en heet nu: haarlem-share-1.0(-SNAPSHOT).jar

Voor het deployen van amp files: zie online alfresco documentatie: http://docs.alfresco.com/5.2/tasks/amp-install.html