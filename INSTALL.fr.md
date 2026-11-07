# Installer un skill TravelSkills

Un skill est un ensemble d'instructions et d'exemples qui montre à un assistant IA comment travaille un pro du voyage. Vous l'installez une fois. L'assistant s'en sert ensuite chaque fois que votre demande s'y rapporte.

Ce guide prend `travel-planner` comme exemple. Aucun code, environ 5 minutes.

## Claude (claude.ai ou l'application de bureau)

1. **Téléchargez le fichier ZIP** (un dossier compressé) sur [travelskills.io/fr/skills/travel-planner](https://travelskills.io/fr/skills/travel-planner). Ne le décompressez pas : Claude lit le fichier tel quel.
2. **Ouvrez Claude** dans votre navigateur ou dans l'application de bureau, et connectez-vous.
3. **Allez dans Customize, puis Skills.** Lien direct : [claude.ai/customize/skills](https://claude.ai/customize/skills). Les menus peuvent rester en anglais selon la langue de votre interface.
4. **Ajoutez un skill et choisissez l'envoi d'un fichier.** Sélectionnez `travel-planner.zip`.
5. **Activez le skill.** Vérifiez que `travel-planner` apparaît dans votre liste de skills, interrupteur activé.
6. **Si Claude demande l'exécution de code,** ouvrez les réglages (Settings), puis Capabilities, et activez l'exécution de code et la création de fichiers. Le skill en a besoin pour lire ses fichiers de référence.
7. **Essayez-le.** Ouvrez une nouvelle conversation et collez une vraie demande, par exemple : « Réécris ce descriptif d'hôtel pour mes clients, un couple de soixante ans qui cherche le calme. » Collez ensuite le descriptif.

Ce que vous obtenez : un brouillon pour votre client, et en dessous une liste « Pour le planner » de ce qu'il faut vérifier avant l'envoi. Relisez avant d'envoyer, comme pour le travail d'un assistant.

**Équipes et organisations.** Avec les offres Claude Team et Enterprise, le skill se partage depuis Customize > Skills, avec les commandes Share ou Publish to org.

### En cas de problème

- **Claude dit ne pas trouver SKILL.md.** Le ZIP a été décompressé puis recompressé sur votre ordinateur. Téléchargez à nouveau le fichier d'origine et envoyez-le tel quel.
- **Vous ne voyez pas Skills.** Les skills ne sont peut-être pas disponibles avec votre offre. Consultez l'aide d'Anthropic pour votre offre.
- **Claude ne semble pas utiliser le skill.** Vérifiez que son interrupteur est activé, puis citez-le dans votre demande : « Utilise le skill travel-planner pour… »

## ChatGPT

Testé sur Claude. ChatGPT accepte le même format de skill, mais nous ne l'avons pas encore testé. Si vous l'essayez, dites-nous ce que ça donne.
