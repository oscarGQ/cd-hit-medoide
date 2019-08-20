# Projet cd-hit-medoide
cd-hit-medoide: 
  Algorithme permettant de corriger la sortie de l'alogorithme de clustérisation de séquences CD-HIT-est.
  Prend entré la sortie.clstr de l'algorithme CD-HIT-est, le fichier des séquences de gènes à clusteriser et le chemins vers les fichiers des contigs dont sont issus les gènes.
  Renvoie les fichier des séquences de gènes représentatifs des clusters ainsi que la fiche descriptive de ces gènes et cela avant et après élimination de la redondance finale.
  Nécessite pour fonctionner les outils externes parallel, blastn, seqkit.

iteratif-medoide:
  Algorithme permettant de concaténer 2 fichiers de gènes en éliminant la redondance à l'image de cd-hit-2d. Sélection du gène représentatnt en se basant sur l'origine du gène, le nombre de gènes que compose le cluster de clutérisation du gène et la taille du gène.
  Prend en entré 2 fichiers de gènes non redondants ainsi que les fichiers .stat associés générés via cd-hit-medoide.
  Renvoie le fichier de concaténation des gènes non redondant ainsi que le fichier .stat associé.
  Nécessite pour fonctionner les outils externes parallel, blastn, seqkit.
