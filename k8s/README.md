# Kubernetes

Aucun manifeste Kubernetes n'a été écrit : le projet tourne dans le service Onyxia `vscode-pyspark`, lancé depuis le catalogue
d'Onyxia, qui crée lui-même le pod. Spark tourne en mode `local[4]` dans ce pod. Les ressources appliquées au pod sont décrites
dans `docs/pipeline.md` (section « Ressources du run ») et le quota du namespace dans `docs/historique.md`.
