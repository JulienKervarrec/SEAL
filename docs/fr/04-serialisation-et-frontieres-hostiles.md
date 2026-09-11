# Serialisation et frontieres hostiles

Les objets serialises franchissant une frontiere de confiance doivent etre consideres hostiles.
Load valide le flux avec le SEALContext mais ne prouve ni origine ni integrite cryptographique.
Les ciphertexts SEAL ne sont pas authentifies : le protocole doit ajouter son propre mecanisme.
La compression d une SecretKey peut en theorie reveler des informations par sa taille.
Les decryptions partagees peuvent aussi exposer la cle selon le modele d attaque.
Les pools ThreadLocal ne doivent pas etre partages entre threads et sont dangereux avec les finalizers .NET.
La documentation de securite doit guider l architecture avant toute optimisation.

Suite : [05 — Limites et verification](05-limites-et-verification.md).
