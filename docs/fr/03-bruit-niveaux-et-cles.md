# Bruit, niveaux et cles

Le bruit protege le message mais doit rester sous la capacite de dechiffrement du schema exact.
Les multiplications font croitre taille et cout des ciphertexts.
Les RelinKeys ramenent un produit vers une representation plus compacte.
Les GaloisKeys autorisent rotations et conjugaison necessaires aux calculs vectorises.
En CKKS, rescale_to_next reduit echelle et modulus en descendant la chaine de niveaux.
Les operandes doivent partager des parameters_id et echelles compatibles avant certaines operations.
La profondeur multiplicative doit etre planifiee avant de choisir les parametres.

Suite : [04 — Serialisation et frontieres hostiles](04-serialisation-et-frontieres-hostiles.md).
