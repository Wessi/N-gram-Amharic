# N-gram-Amharic

## Natural Language Processing (NLP) - Assignment 1\n",
    "## Instructor:\n",
    "* **Fantahun B. (Ph.D.)**\n",
    "### Student:\n",
    "* **Name:** Wesagn Dawit\n",
    "* **ID:** GSR/5257/15\n",
    "* **Program:** MSc in Artificial Intelligence\n",
    "#### Introduction:\n",
    "* This individual assignment is based on one version of the General Purpose Amharic Corpus (GPAC). The assignment involved building **n-gram language models for n values of n = 1,2,3,4** and evaluating their performance **intrinsically and extrinsically**. For intrinsic evaluation, **perplexity** was calculated by determining the probabilities of n-grams in the corpus and generating random sentences based on these n-grams. Since the corpus lacked labels, **text generation** served as the extrinsic evaluation method. Extrinsically, the models' ability to accurately assign probabilities to new sequences was assessed by calculating the likelihoods of test sentences under each model. Extrinsic evaluation utilizes the language models to generate text, with quality assessment based on probability. Higher probabilities indicate better generalization as the model was more likely to generate that sentence. Given an unlabeled corpus, text generation was employed to evaluate the n-gram models, creating random sentences for n=1 to 4. The generated sentences were evaluated based on their coherence and ability to make sense. The higher the n-gram model, the more coherent the generated sentence is. However, the higher the n-gram model, the more data is required to train the model. Therefore, the n-gram model should be chosen based on the available data and I think that is why our instructor specifically asked us to create n-gram models for n values of n = 1,2,3,4."
   
