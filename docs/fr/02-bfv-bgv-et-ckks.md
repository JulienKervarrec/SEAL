# BFV, BGV et CKKS

BFV et BGV calculent exactement sur des entiers modulo plain_modulus.
CKKS encode des nombres reels ou complexes de maniere approximative avec une echelle.
Le choix du schema depend donc de la semantique attendue, pas seulement de la vitesse.
BatchEncoder place plusieurs entiers dans les slots BFV ou BGV pour un traitement SIMD.
CKKSEncoder gere les slots complexes et la precision repartie entre echelle et moduli.
Un resultat CKKS doit etre interprete avec une marge d erreur numerique explicite.
Comparer des Ciphertext a des valeurs en clair n est pas une operation native generale.

Suite : [03 — Bruit, niveaux et cles](03-bruit-niveaux-et-cles.md).
