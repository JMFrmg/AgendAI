# AgendAI
Projet réalisé en équipe à l'occasion du Hacking Industry Camp (jenvier 2021)
L'objectif était de réaliser une mise à jour automatique d'agenda électronique. Une application web responsive a été créée avec python Django. Notre application comprend deux fonctions principale. 
* L'utilisateur peut prendre en poto un QR relatif à un évènement (concert, film...). Les informations sont extraites du QR code, sont récupérées par l'application web et intégrées à un agenda électronique. 
* La seconde fonctionnalité fait appel à de l'intelligence artificielle. L'utilisateur peut prendre une image, par exemple d'un concert, avec son smartphone. La photo est envoyé à un modèle de Deep Learning entraîné sur la plateforme Google AI. Le modèle nous renvoie le nom de l'écènement et la date. Le sinformations sont alors intégrées automatiquement à un agenda électronique.
Technos utilisées : Python - Django - Javascript - librairie python PIL.Image - pyzbar.pyzbar.decode (décoder les QRcode en python) - Google AI
