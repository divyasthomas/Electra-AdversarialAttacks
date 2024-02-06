## Improving Financial Sentiment Classification on ELECTRA using Adversarial Attacks.

This project delves into sentiment analysis in the financial domain, with a focus on classifying text into positive, negative, or neutral sentiments. 
Utilizing an initially pre-trained ELECTRA-small model designed for general sentiment classification, a baseline model was crafted on financial sentiment data. 
This model achieved an accuracy of 85.47% on the Financial PhraseBank dataset, with the primary source of error being misclassification between positive and neutral sentiment classes.
While attempts to enrich the model's financial vocabulary using the FinRAD dataset led to a decrease in accuracy, the introduction of successful adversarial attacks notably improved baseline model performance. 
Specifically, the model trained on data augmented with TextFooler-generated adversarial examples exhibited a 4.68% accuracy increase to 90.15%.
This approach not only bolstered accuracy but also alleviated misclassifications between positive-neutral classes, addressing a significant challenge observed in the baseline model. 
Another important outcome lies in the model's adept generalization to a novel and challenging problem on an unseen dataset, setting it apart from other contemporary works in literature that often rely on a subset of the Financial PhraseBank for fine-tuning.








