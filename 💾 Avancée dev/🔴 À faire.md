* i18n -> @Ninjdai
* Système d'inventaires
	* classe de base inventory extensible (pour inventaires de mobs, npcs, joueurs, objets (coffres, jarres...), etc)
	* loot tables (data-driven, cf mc)
* Joueur:
	* Character maker
	* Classes, ability tree, stats
* NPCs:
	* Implémentation sous forme de classe (sous-classe de entity ?)
	* Dialogues dynamiques (pouvant changer selon les actions du joueur, les évènements, etc)
	* Stats
	* Sauvegarde d'état sur serveur
	* Neutres, aggressifs, amicaux -> réputation
* Ennemis:
	* Implémentation sous forme de classe (sous-classe de entity ?)
	* Stats
	* Spawn:
		* Dépendant des régions
		* de la météo
		* des [[saisons mērēliennes]]
		* Impact des joueurs (sur l'éther par mobs tués) ?
		* cf. [[cycles éthéréens]]
* Combat:
	* Grid-based
	* Voir game-design
* Saisons, biomes, météo & co