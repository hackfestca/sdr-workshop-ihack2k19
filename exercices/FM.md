![SDR](../img/img1.jpeg)
# Écoute d'une station FM
**Note: Les instructions des exercices sont faites pour le logiciel GQRX et Linux. Cependant, les mêmes principes s'appliquent pour les autres logiciels d'écoute de signaux**

À partir du moment où vous avez installé **GQRX**, vous devriez pouvoir écouter une station FM presque directement. Dans cet exemple, j'écoute la station diffusant sur le 88.3 Mhz ([ICI Radio-Canada Première](https://ici.radio-canada.ca/premiere) dans les Laurentides).

Voici les paramètres importants:

- **Mode:** WFM Mono (Wide FM)
- **Filter shape:** Normal
- **AGC (Automatic Gain Control):** Medium

Vous devriez commencer par essayer en mode "Mono"; C'est habituellement plus clair pour des signaux plus faibles.

![GQRX](../img/img2.png)

Voilà! Vous êtes maintenant en mesure d'écouter la radio "offline" comme dans le bon vieux temps!

Vous devriez aussi aller voir dans le menu **View > RDS**. Il est ainsi possible de décoder les signaux RDS (Radio Data System). Habituellement, ce signal est généralement utilisé par les stations pour diffuser leur nom et le titre des pièces.

## Sommaire
1. [**Préparation:**](exercices/installation.md) Installation d'un logiciel de SDR
2. [**Premier exercice:**](exercices/FM.md) Écoute d'une station FM
3. [**Troisième exercice:**](exercices/ADS-B.md) Décodage de signaux ADS-B (Avions)
4. [**Deuxième exercice:**](exercices/POCSAG.md) Décodage de signaux FLEX (Pagette)
