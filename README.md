# MVSEP-MDX23 Colab 2.4
Adaptation de l'algorithme MVSep-MDX23 pour Colab, en français et avec quelques ajustements :

[MVSEP-MDX23-Colab_v2.4_FR](https://colab.research.google.com/github/GiGiDKR/MVSEP-MDX23-Colab_v2/blob/v2.4/MVSep-MDX23-Colab-French.ipynb)

Changements récents :
<font size=2>

**v2.4**
* Modèles BS-Roformer de viperx ajoutés
* Modèle MDX-InstHQ4 ajouté en option
* Sortie FLAC
* Contrôler le gain du volume d'entrée
* Option filtrer les voix en dessous de 50 Hz
* Meilleur algorithme de chunking (pas de clics)
* Un peu de nettoyage de code



</font>
<br>

<details>
    <summary>Journal des modifications complet :</summary>

[**v2.3**](https://github.com/jarredou/MVSEP-MDX23-Colab_v2/tree/v2.3)
* Modèle HQ3-Instr remplacé par VitLarge23 (grâce à MVSep)
* Traitement MDXv2 amélioré (grâce à Anjok)
* Algo BigShifts amélioré (v2)
* Traitement BigShifts ajouté à MDXv3 et VitLarge
* Traitement par lots de dossiers plus rapide

<br>
<font size=2>
<br>

[**v2.2.2**](https://github.com/jarredou/MVSEP-MDX23-Colab_v2/tree/v2.2)
* Amélioration du code de segmentation MDXv3 (grâce à HymnStudio)
* Modèle de démonstration D1581 remplacé par le nouveau modèle InstVocHQ MDXv3.
<br>

**v2.2.1**
* Ajout d'une fonctionnalité de poids personnalisés
* Correction de quelques bugs
* Entrée fixe : vous pouvez désormais utiliser un fichier ou un dossier comme entrée
<br>

**v2.2**
* Ajout de la compatibilité MDXv3 
* Ajout du modèle de démonstration MDXv3 D1581 dans l'ensemble multibande de tige de chant.
* Ajout du SRS pleine bande VOC-FT au lieu de UVR-MDX-Instr-HQ3.
* Ajout de la fonctionnalité 2 pistes : sortie uniquement des voix / instruments (traitement plus rapide)
* Ajout d'une option de format de sortie 16 bits
* Ajout de "l'astuce BigShift" pour les modèles MDX
* Ajout de valeurs de chevauchement séparées pour MDX, MDXv3 et Demucs
* Réglage fin de la compensation de volume fixe pour MDX-VOC-FT
<br>

[**v2.1 (par deton24)**](https://github.com/deton24/MVSEP-MDX23-Colab_v2.1)
* Mis à jour avec MDX-VOC-FT au lieu de Kim Vocal 2
<br>

[**v2.0**](https://github.com/jarredou/MVSEP-MDX23-Colab_v2/tree/2.0)
* Mis à jour avec les nouveaux modèles Kim Vocal 2 et UVR-MDX-Instr-HQ3
* Traitement par lots de dossiers
* Correction du saignement des hautes fréquences dans le chant
* Compensation de volume fixe pour les modèles MDX
<br>
</font>
</details>

---

Création originale de [ZFTurbo/MVSep](https://github.com/ZFTurbo/MVSEP-MDX23-music-separation-model)

---

Ajustements de [Jarredou](https://github.com/jarredou/MVSEP-MDX23-Colab_v2)

Traduction de [GiGiDKR](https://github.com/GiGiDKR)
