# Limites et verification

Microsoft SEAL ne fournit ni authenticite des ciphertexts ni circuit privacy automatique.
Certaines operations sur plaintext ne sont pas constantes en temps vis-a-vis de cet operande.
Les benchmarks autorisent des parametres non surs et ne constituent pas des exemples de production.
Les versions anciennes peuvent manquer de durcissements importants sur les entrees non fiables.
Ce parcours repose sur EncryptionParameters, SEALContext, Encryptor, Evaluator et la politique SECURITY.
Aucune installation, compilation, execution ou mesure de performance nouvelle n a ete effectuee.
La selection de parametres de production requiert une revue par des specialistes FHE.
Pour verifier, consulter native/tests, dotnet/tests et les exemples 1 a 6 du depot.
