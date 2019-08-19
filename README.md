# cd-hit-medoide
# Algorithme permettant de corriger la sortie de l'alogorithme de clustérisation de séquences CD-HIT-est.
# Prend entré la sortie.clstr de l'algorithme CD-HIT-est, le fichier des séquences de gènes à clusteriser et le chemins vers les fichiers des contigs dont sont issus les gènes.
# Renvoie les fichier des séquences de gènes représentatifs des clusters ainsi que la fiche descriptive de ces gènes et cela avant et après élimination de la redondance finale.
# Nécessite pour fonctionner les outils externes parallel, blastn, seqkit
