# StationMeteoConnectee_5GI
Projet collaboratif de station météo connectée avec visualisation mobile

## Description

 **La Station Météo Connectée est un projet personnel de surveillance des conditions météorologiques locales. Elle mesure en temps réel plusieurs paramètres environnementaux, comme la température, l'humidité, la pression atmosphérique et l'intensité lumineuse. Les données collectées sont accessibles via une application mobile, permettant de consulter l’historique, observer les variations climatiques locales et recevoir des notifications pour des conditions extrêmes. Cette station est idéale pour surveiller le climat dans un jardin, planifier des activités en extérieur ou ajuster des systèmes de chauffage et ventilation selon les données locales.**

## Fonctionnalités

<ul>
  <li>Mesure en temps réel des conditions environnementales</li>
        <ul>
        <li>Température</li>
        <li>Humidité</li>
        <li>Pression atmosphérique</li>
        <li>Intensité lumineuse</li>
        </ul>
  <li>Application mobile connectée pour</li>
            <ul>
        <li>Consulter l’historique des données météo.</li>
        <li>Humidité</li>
        <li>Observer les variations climatiques locales.</li>
        <li>Recevoir des notifications en cas de conditions extrêmes (comme des hausses soudaines de température ou des changements brusques de pression).</li>
        </ul>
  
  <li>Stockage des données pour analyses et rapports futurs.</li>
</ul>

## Utilité

Ce dispositif est pensé pour :

<ul>
        <li>Observer les conditions météorologiques dans un jardin ou un espace extérieur.</li>
        <li>Aider à planifier les activités extérieures selon les données locales.</li>
        <li>Pression atmosphérique</li>
        <li>Améliorer l’efficacité des systèmes de chauffage et de ventilation dans une maison en se basant sur les conditions climatiques mesurées.</li>
        </ul>


## Schéma du Projet

Le projet se décompose en plusieurs composants :

<ol>
  <li><strong>Capteurs</strong> : Mesurent les paramètres environnementaux (température, humidité, pression, luminosité).</li>

  <li><strong>Contrôleur Arduino</strong> : Collecte les données des capteurs et les envoie vers le serveur ou directement vers l’application mobile.</li>

  <li><strong>Application mobile</strong> : Affiche les données et envoie des notifications aux utilisateurs.</li>

  <li><strong>Serveur Backend</strong> : Enregistre l’historique et gère les notifications.</li>
</ol>

## Technologies et composants  Utilisées

<ul>
        <li><strong>Arduino</strong> pour la collecte des données.</li>
        <li><strong>Capteurs</strong> de température, d'humidité, de pression et de luminosité.</li>
        <li><strong>Module Wi-Fi</strong>(ex. : ESP8266) pour la communication sans fil.</li>
        <li><strong>Backend</strong> avec Node.js et Express pour gérer le stockage de données et l’envoi de notifications.</li>
        <li><strong>Application mobile</strong> développée en Flutter  pour une compatibilité multiplateforme (iOS et Android).</li>
        </ul>


