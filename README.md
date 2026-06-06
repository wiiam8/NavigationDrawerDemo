# LAB 10 - Navigation Drawer et Fragments

## Description

Ce projet est une application Android développée en Java qui démontre l'utilisation d'un Navigation Drawer avec plusieurs fragments.

L'objectif principal est de gérer dynamiquement l'affichage de plusieurs fragments dans une seule activité principale à travers un menu latéral.

## Fonctionnalités

L'application permet de :

- Afficher un menu latéral de navigation
- Naviguer vers un premier fragment avec un fond rose
- Naviguer vers un deuxième fragment avec un fond bleu
- Afficher une liste d'éléments à travers un ListFragment
- Remplacer dynamiquement les fragments dans une zone dédiée
- Utiliser un FloatingActionButton

## Technologies utilisées

- Java
- Android Studio
- XML Layouts
- Navigation Drawer
- Fragments
- ListFragment
- Material Components
- DrawerLayout
- NavigationView

## Structure du projet

```text
NavigationDrawerDemo/
│
├── app/src/main/java/com/example/navigationdrawerdemo/
│   ├── MainActivity.java
│   ├── BlankFragment.java
│   ├── BlankFragment2.java
│   └── FragmentList.java
│
├── app/src/main/res/layout/
│   ├── activity_main.xml
│   ├── app_bar_main.xml
│   ├── nav_header_main.xml
│   ├── fragment_blank.xml
│   └── fragment_blank2.xml
│
├── app/src/main/res/menu/
│   └── activity_main_drawer.xml
│
├── app/src/main/res/drawable/
│   ├── ic_home.xml
│   ├── ic_dashboard.xml
│   └── ic_list.xml
│
└── README.md
```
# Fragments
## Fragment 1

Le premier fragment affiche un fond rose avec le texte :

Fragment 1
Fragment 2

Le deuxième fragment affiche un fond bleu avec le texte :

## Fragment 2
Fragment List

Le troisième fragment affiche une liste simple contenant :

Item 1
Item 2
Item 3
...
Item 10
Fonctionnement

Le menu latéral contient trois éléments :

Élément du menu	Fragment affiché
Fragment 1	BlankFragment
Fragment 2	BlankFragment2
Fragment List	FragmentList

Lorsqu'un élément du menu est sélectionné, MainActivity utilise FragmentManager pour remplacer dynamiquement le contenu du FrameLayout.

# Dépendances principales

Les dépendances utilisées dans le projet sont :

implementation 'androidx.appcompat:appcompat:1.6.1'
implementation 'androidx.constraintlayout:constraintlayout:2.1.4'
implementation 'com.google.android.material:material:1.12.0'

Ou avec Kotlin DSL :

implementation("androidx.appcompat:appcompat:1.6.1")
implementation("androidx.constraintlayout:constraintlayout:2.1.4")
implementation("com.google.android.material:material:1.12.0")
Exécution

# Pour exécuter le projet :

Ouvrir le projet avec Android Studio.
Synchroniser Gradle.
Lancer l'application sur un émulateur ou un téléphone Android.
Ouvrir le Navigation Drawer.
Sélectionner les différents fragments.
Vidéo démonstrative

# La vidéo démonstrative du projet est disponible ici :

[Voir la vidéo de démonstration ](https://drive.google.com/file/d/1VAbHwBwkjrX3b41_a1qEzKQtvruC4ha6/view?usp=sharing)
