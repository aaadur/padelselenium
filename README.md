# padel selenium
Container pour exécuter des robots selenium en python

Image utlisés
  Alpine
  Selenium 
  Firefox
  Python + library 


https://labs.play-with-docker.com/

Utilisation VM Azure pour création de l'image
Cnx Putty

Utiliser Putty gen
Charger la clé générée par Azure (*.pem) et sauvegarder la en clé private (save private key)
configurer putty en utilisant le fichier généré (*.ppk) en le paramétrant dans ssh/auth


touch a
-> copier dans a : git clone https//.....(prendre l'adresse dans github)
$(cat a)
cd padelselenium
docker image build -t aaadur/padelselenium .
docker login -u a...
docker image push aaadur/padelselenium
