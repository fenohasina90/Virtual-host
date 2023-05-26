# Projet Virtual Hosts avec Ansible

Ce projet utilise Ansible pour automatiser la configuration des Virtual Hosts d'Apache. Il vous permet d'installer Apache et de créer des Virtual Hosts avec une URL spécifique.

## Prérequis

Avant d'exécuter ce projet, assurez-vous d'avoir les éléments suivants :

- Ansible installé sur votre machine
- Accès administratif pour installer des packages sur l'hôte cible

## Installation

Suivez les étapes ci-dessous pour configurer l'environnement et exécuter le script Ansible :

1. Installez Ansible en suivant les instructions officielles : [Ansible Installation Guide](https://docs.ansible.com/ansible/latest/installation_guide/index.html).

2. Clonez ce dépôt GitHub sur votre machine locale :

3. Accédez au répertoire cloné :

4. Configurez les Virtual Hosts :

- Ouvrez le fichier `files/www.HEI.school.conf` dans un éditeur de texte.
- Modifiez les directives de configuration selon vos besoins, en ajoutant les paramètres spécifiques à votre Virtual Host.

5. Exécutez le script Ansible pour créer les Virtual Hosts :

Assurez-vous d'avoir les droits administratifs nécessaires pour exécuter les tâches.

6. Vérifiez qu'Apache est correctement configuré et que les Virtual Hosts sont actifs.

## Structure du projet

- Le répertoire `ansible` contient les fichiers nécessaires pour automatiser la configuration des Virtual Hosts.
- Le fichier `playbook.yml` définit les tâches Ansible pour installer Apache et créer les Virtual Hosts.
- Le répertoire `files` contient les fichiers de configuration Apache pour chaque Virtual Host.

## Auteurs

Ce projet a été développé par [Mangalahy Fenohasina](https://github.com/fenohasina90).



