# Calculer sur des chiffres

Microsoft SEAL permet d evaluer certaines fonctions directement sur des donnees chiffrees.
Le client chiffre avec une cle publique ou symetrique puis conserve la cle secrete pour dechiffrer.
L Evaluator additionne et multiplie des Ciphertext sans acceder aux valeurs en clair.
Chaque operation augmente cependant le bruit ou consomme une partie de la profondeur disponible.
Les EncryptionParameters fixent scheme, poly_modulus_degree et chaines de moduli.
SEALContext valide ces choix et construit les niveaux utilises par les objets cryptographiques.
Le chiffrement homomorphe ne remplace ni authentification ni controle d acces.

Suite : [02 — BFV, BGV et CKKS](02-bfv-bgv-et-ckks.md).
