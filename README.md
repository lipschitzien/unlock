# unlock

Introduction: C’est un projet composé par 3 parties: Machine Learning(Python), Android(Java), Arduino(Python).

Il s'agit d'un système de serrure intelligente à reconnaissance faciale(Eigenface) qui peut être utilisé pour contrôler l'accès à une boîte aux lettres ou à d'autres appareils domestiques.

Le système est composé de 2 éléments principaux :

Un Raspberry Pi 4 qui sert de centre de contrôle, qui contrôle la serrure électronique. Une application mobile qui permet aux utilisateurs de contrôler la serrure à distance.

L'application mobile permet aux utilisateurs de contrôler la serrure à distance avec mot de passe. L'application demande aux utilisateurs de s'inscrire en fournissant leur nom, leur mot de passe et l'adresse IP du Raspberry Pi. Une fois connectés, les utilisateurs peuvent ouvrir ou fermer la serrure en appuyant sur un bouton. L'application enregistre également l'historique des opérations effectuées sur la serrure.

Le système d'intelligence artificielle sur Rasoberry Pi a été testé avec succès sur un ensemble de données de 500 visages. J'ai utilisé l'algorithme Eigenface, le premier algorithme de reconnaissance faciale. Le taux de reconnaissance faciale est de 95%.

En perspective, on peut faire:

L'utilisation d'un algorithme de reconnaissance faciale plus sophistiqué, tel que le deep learning(CNN), pour améliorer le taux de reconnaissance faciale. L'ajout de fonctions supplémentaires, telles que la possibilité de contrôler d'autres appareils domestiques, tels que des lumières ou des thermostats.

Conclusion

Ce projet est un exemple de la manière dont la technologie de la reconnaissance faciale peut être utilisée pour créer des systèmes intelligents et pratiques. Le système présente un certain nombre d'avantages, notamment :

La sécurité : le système permet de contrôler l'accès à une zone de manière sécurisée. La commodité : le système permet aux utilisateurs d'ouvrir ou de fermer la serrure à distance. L'efficacité : le système peut être utilisé pour contrôler d'autres appareils domestiques.

**__Le projet est terminé en termes de fonctionnalités de base, les interfaces sont en cours de développement, avec une date de livraison prévue en février. **__

<img width="289" alt="m1" src="https://github.com/lipschitzien/unlock/assets/110629446/1aed8340-f087-4457-957b-0417a9aa63ba">

<img width="310" alt="m5" src="https://github.com/lipschitzien/unlock/assets/110629446/1f357495-9089-48db-960c-b54f3b34ebff">

<img width="299" alt="m3" src="https://github.com/lipschitzien/unlock/assets/110629446/145e2b35-7e78-4dcb-8263-6fa19f05b644">

<img width="292" alt="m4" src="https://github.com/lipschitzien/unlock/assets/110629446/9be9496c-9d5c-43de-b253-18f9fe1640af">

