# English to French Language-translation
Seq2Seq Character level model
1. The character level model predicts almost all single words corectly. For example: Hi. -> Salut!. It even adds the exclamation mark!
2. The model translated smaller sentences with little ambiguity. For example: 
 * I fled. -> Je me suis partie. (which means "I left" from Google translate)
 * Go now. -> Marchez-le. (which means "walk it" from Google translate)
 
Seq2seq word level model
1. The word level model is not able to predict the noun in some cases. For example: In "Are you tom", "are you" is predicted correctly. But not Tom.
2. The verb is not predicted correctly in the second sentence. "I want to walk"is predicted as "je veux des travail"(I want work)
