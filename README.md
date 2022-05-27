# Adversarial_Attacks

Nowadays, neural network models have achieved state-of-the-art results in many natural language processing tasks. Nevertheless, small perturbations of the input can easily fool a language model, which may lead to further misclassification. There are not sufficient studies on adversarial attack for Russian language. We explore the possibilities to adopt existing attacks to the Russian language. Also, we are going to introduce our own adversarial attacks, which will take into account the special Russian morphology. 

We present five adversarial black-box attacks in order to evaluate the possible quality of neural network models on input data for the Russian language. In our work, we solve the problem of Recognizing Textual Entailment for Russian using two types of language models.

## Code:

Train and attack the model - [code](https://github.com/Kostrykina18/Adversarial_Attacks/blob/main/train%2Battack.ipynb)

Attacks:

1. Replacing a word with a synonym - [code](https://github.com/Kostrykina18/Adversarial_Attacks/blob/main/attack1_vectors.ipynb)
2. Violation of agreement - [code](https://github.com/Kostrykina18/Adversarial_Attacks/blob/main/attack2_cases.ipynb)
3. Govern violation: verb level - [code](https://github.com/Kostrykina18/Adversarial_Attacks/blob/main/attack3_1_prep_verb.ipynb)
4. Govern violation: preposition level - [code](https://github.com/Kostrykina18/Adversarial_Attacks/blob/main/attack3_2_prep_prep.ipynb)
5. Changing the tense of a verb - [code](https://github.com/Kostrykina18/Adversarial_Attacks/blob/main/attack4_verbs.ipynb)

## Data

TERRa (Textual Entailment Recognition for Russian) - [folder](https://github.com/Kostrykina18/Adversarial_Attacks/tree/main/TERRa%20dataset)
