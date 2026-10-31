# QuizTestUniversel

## But du projet

Ce projet a pour but de créer un moyen simple de réviser à partir d'un formulaire JSON contenant des questions et leurs réponses.

Il propose deux modes de révision :

- **Quiz** : répondre aux questions et vérifier ses réponses ;
- **Flashcards** : réviser les questions et afficher les réponses progressivement.

## Format JSON attendu

Le fichier JSON doit suivre cette structure :

```json
{
	"title": "Mon Quiz",
	"questions": [
		{
			"id": "q1",
			"prompt": "La question ?",
			"options": [
				{"id": "a", "text": "Réponse A"},
				{"id": "b", "text": "Réponse B"},
				{"id": "c", "text": "Réponse C"},
				{"id": "d", "text": "Réponse D"}
			],
			"correct_option_id": "a",
			"explanation": "Pourquoi A...",
			"hint": "Un indice...",
			"correct_feedback": "Bravo !",
			"incorrect_feedback": "Pas tout à fait."
		}
	]
}
```

