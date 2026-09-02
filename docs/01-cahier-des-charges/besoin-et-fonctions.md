# Cahier des charges fonctionnel

> Livrable L3 · Jalon J2.

## Énoncé du besoin

À qui le dispositif rend-il service ?
Aux élèves, aux enseignants et aux établissements de formation en automatisme, électronique et mécatronique.

Sur quoi agit-il ?
Sur une pièce transportée par un convoyeur à bande, en assurant sa détection, son positionnement et son marquage automatique.

Dans quel but ?
Permettre l'étude et la mise en œuvre d'un système automatisé de production afin d'apprendre la détection, la commande d'actionneurs, la programmation, la synchronisation des opérations et la conception d'une carte électronique.

Ces réponses sont adaptées à un diagramme de la « bête à cornes » si c'est le type de questionnaire que tu remplis.

## Fonctions de service et contraintes

| Réf. | Fonction | Critère | Niveau visé | Flexibilité |
|------|----------|----------|-------------|-------------|
| FS1 | Transporter, détecter et marquer automatiquement une pièce. | Fonctionnement automatique, marquage correct et synchronisation du cycle. | Une pièce est détectée, marquée puis évacuée sans erreur. | F0 |
| FC1 | Être alimenté en basse tension et garantir la sécurité des utilisateurs. | Alimentation 12 V CC, composants protégés, fonctionnement fiable en milieu pédagogique. | Conforme aux exigences d'un dispositif didactique. | F1 |

## Déclinaison des exigences fonctionnelles du programme

| Réf. CDC | Exigence | Déclinaison sur ce projet | Vérification prévue |
|-----------|----------|---------------------------|---------------------|
| EF-01 | Intention pédagogique explicite | Le convoyeur didactique permet d'étudier la détection, la commande d'actionneurs, la programmation d'un cycle automatisé et la conception d'une carte électronique. | Validation de la conformité avec les objectifs pédagogiques et les activités prévues. |
| EF-02 | Mesure et action sur le monde physique | Le système détecte la présence d'une pièce à l'aide d'une barrière optique, pilote le moteur du convoyeur et commande l'actionneur de marquage. | Essais fonctionnels de détection, de déplacement et de marquage sur plusieurs cycles. |
| EF-03 | Restitution exploitable hors internet | Les informations de fonctionnement sont indiquées par des LED d'état et le comportement du système est directement observable. | Vérification du fonctionnement complet sans connexion Internet. |
| EF-04 | Prise en main élève ≤ 10 min | Interface simple avec interrupteur général, mise sous tension et lancement rapide du cycle automatique ou pas à pas. | Test auprès d'élèves : prise en main et réalisation d'un premier cycle en moins de 10 minutes. |
| EF-05 | Transportable, ≤ 60 × 60 × 60 cm, mise en service ≤ 5 min | Convoyeur compact en contreplaqué, alimentation 12 V unique, raccordement rapide et faible encombrement. | Mesure des dimensions, contrôle du poids et chronométrage de la mise en service. |
