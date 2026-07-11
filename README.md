# Alimentation stabilisée réglable (SI1)

Situation d'intégration 1 – Qualification Électricien-Automaticien
Année académique 2022-2023

## Description

Alimentation stabilisée réglable 0-24V DC construite autour d'un régulateur LM317, avec transformateur abaisseur, redressement, filtrage et réglage de la tension de sortie par potentiomètre. Premier projet réalisé dans la section électricien-automaticien.

## Étude réalisée

- Schéma de principe de l'alimentation stabilisée
- Relevés de tension à vide, potentiomètre au minimum et au maximum
- Relevés de tension en charge, au minimum et au maximum
- Vérification du comportement du régulateur LM317 selon la charge et le réglage

## Matériel principal

- Transformateur abaisseur 230V / ~24V AC
- Pont redresseur + condensateurs de filtrage
- Régulateur de tension LM317
- Potentiomètre de réglage de sortie
- Fusibles de protection (T80mA, F0.5A)
- LED de signalisation

## Conception mécanique

Le boîtier (socle et schéma de câblage) a été dessiné en CAO. Les fichiers sources sont disponibles dans [`schema/`](schema/) :
- `socle.dxf` — plan du socle
- `schema_de_cablage.dxf` — schéma de câblage interne

## Rapport complet

Le rapport complet (schémas de principe, mesures à vide et en charge, photos de la réalisation, annexes mécaniques) est disponible dans [`docs/rapport_alimentation_stabilisee.pdf`](docs/rapport_alimentation_stabilisee.pdf).