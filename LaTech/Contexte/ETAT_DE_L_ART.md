1.  []Résumé
    Ce travail de fin d’études boucle notre cursus universitaire pour l'obtenstion d'un Diplome en Génie Electronique à la Faculté Des Sciences de l'Université d'Etat d'Hiti (FDS-UEH) durant l’année académique 2019-2020.

    La gestion des données géothechniques en Haïti ne dispose pas d’un système informatisé centralisé. Dans ce mémoire, nous vous présentons une solution se basant sur la conception et la réalisation d'un tel systeme.

    La totalité des codes est disponible en ligne sur GitHub :https://github.com/geotech
    L’application est hébergé par AWS à l’adresse: https://geotech.ht

    Mots-clés : Données spatiales, Croquis.

    Abstract
    The sketch is an old form of communication that was used to visualize, share and store information. Despite its proven
expressiveness, it has not yet become a used modality in the interaction between humans and computer systems. Geographic
Information Systems (GIS) have special needs for such advanced forms of interaction, because they involve complex and
heterogeneous data structures, which are often difficult to describe by the text or by predicates based on attributes. The objective of
this work is to show the usefulness of the sketch in retrieval spatial information in a particular case which is the geographic data. In
this context, a prototype application of sketch query system is implemented in order to verify the concepts and theories developed.

Keywords : Spatial data, Sketch.

2.  []Remerciments
    Nous réservons quelques lignes pour remercier plusieurs persnones qui ont apporté leur support a la réalisation de GéoTech:
    Merci à l'URGéo pour nous avoir fait confiance et nous donnée ce formidable projet;
    Merci à nos tuteurs ...;
    Merci aux professeurs ...;
    Merci au stagiaire ...;
    Merci à nos beta testeurs ...;
    Merci à la communauté FDS pour ...;
    
3.  [] Glossaire
    Urgéo   : Unité de Recherche en Géosciences
    GIS     : A geographic information system (GIS) is a framework for gathering, managing, and analyzing data.
4.  []Contexte
    L’Unité de Recherche en Géotechnique (URGéo) dans le cadre de ses activités de recherches et de service à
la communauté dispose d’un ensemble de données géotechniques, géophysiques et géologiques. Le projet
consiste à collecter et organiser ces données existantes dans un Système d’Information Géographique (SIG).
L’objectif de ces services est donc de concevoir, développer, tester et installer un système de gestion
informatisée (base des données) à utiliser dans la gestion de l’archive technique de l’URGéo. Cette unité
dispose d'une base de données constituée d’une collection de documents au format PDF (Portable Document
Format). Le format PDF est un standard ouvert d'échange de documents électroniques géré par l’ISO
(International Organization for Standardization). Il souhaite cependant réaliser la migration de cette base vers
un système de gestion plus efficace.
5.  [] Etat de l'art
- Introduction
    Une étude ciblée, approfondie et critique des travaux
(existants) a été réalisée sur les GIS. Elle a permis la maîtrise du domaine de recherche par
l’acquisition des connaissances solides sur les travaux de
recherche réalisés.

- situation actuelle d'Haiti
- Standards et modèles existants 

- Outils de développement 
 Il existe de nombreux outils de développement de vues de supervision. Ceux-ci sont
basés sur des technologies diverses et ont chacun leurs propres avantages et
inconvénients par rapport à notre problématique. Notre principale proble est le protocole permettant les echanges des donnees geotechniques.

- Processus de développement 
La figure III.3 représente le processus de développement centré architecture ainsi que
les acteurs qui interviennent directement dans celui-ci : l’architecte, le développeur, ainsi
qu’éventuellement l’analyste (cette tâche peut être automatisée) [Leymonerie 2004]. 
L’architecte a pour rôle de définir l’architecture qui servira de base au développement
de l’application. Le développeur raffine cette architecture de façon à s’approcher petit à
petit de l’application finale. Pour cela il implémente les composants ainsi que leurs
interactions (les connecteurs) en respectant la structure et les propriétés définies par
l’architecture de départ*
A chaque étape de raffinement l’analyste est en mesure de
vérifier que l’architecture raffinée est conforme à l’architecture du niveau d’abstraction
supérieur. Ce processus permet de garantir que l’application obtenue respecte les
propriétés fonctionnelles, structurelles et comportementales définies par l’architecte en
accord avec le client et les utilisateurs
