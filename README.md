# Migration des données de la BHP

## Présentation

Le projet de migration des données de la BHP vers un autre environnement de recherche a débuté en 2019. Il regroupe deux sous-projets imbriqués : l’alignement du modèle symogih.org vers le CIDOC CRM et SDHSS et la migration proprement dite des données, l’alignement étant l’étape préalable.

Dans le cadre de l’initiative Geovistory, il était prévu d’utiliser la Toolbox comme réceptacle des données de la BHP. L’arrêt de Geovistory fin 2025 a également mis fin au projet de migration vers la Toolbox.

La richesse des données de la BHP et l’attente des chercheurs impliqués dans les projets hébergés par la BHP nous oblige à reprendre ce projet et à le repenser dans le cadre de la nouvelle initiative LOD4HSS et le développement d’un nouvel environnement basé sur des graphes RDF.

Considérant qu’il sera plus facile de repartir des données de la base PostgreSQL pour les transformer en triplets RDF plutôt que de tenter une récupération des données déjà importées dans la Toolbox, un _reboot_ du projet est relancé en septembre 2026

## Documentation et références

### Références

* <https://symogih.org/> : Site de référence
* <https://bhp.ish-lyon.cnrs.fr/> : Base d’hébergement de projet.
* <https://geo-larhra.ish-lyon.cnrs.fr/> : Gazetteer du projet.

### Gestion du projet

* <https://github.com/lod4hss-projects/symogih> : Ce dépôt, dédié à l’importation des données de la BHP vers un nouvel environnement. Le travail déjà réalisé pour l’importation de Geovistory pourra être repris en partie.
* <https://github.com/lod4hss-projects/Alignement_symogih.org> : Dépôt dédié à l’alignement de l’ontologie symogih.org vers CIDOC CRM/SDHSS. Chaque entité du modèle symogih.org fait l’objet d’un ticket et d’une proposition d’alignement.
* <https://github.com/orgs/lod4hss-projects/projects/6> : Gestion du projet d’alignement.
