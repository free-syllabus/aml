## Transformers and Attention

### Required Study Materials

1. **[LSTM is dead. Long Live Transformers](https://www.youtube.com/watch?v=S27pHKBEp30)** (video/29min) by Leo Dirac
2. **[Attention is all you need](https://www.youtube.com/watch?v=rBCqOTEfxvg)** (video/49min) by Lukasz Kaiser from Google Brain

### Alternative Study Materials

1. **[Illustrated transformer](https://jalammar.github.io/illustrated-transformer/)** (blogpost) by Jay Alammar 
2. Paper **[Attention is all you need](https://arxiv.org/abs/1706.03762)** (academic paper) <br>
   This is the original paper if you would be curious. We don't expect you to read it and understand it, but it might be interesting for you to just have a look inside.

### On Session Materials

1. Tokenizer for GPT: https://platform.openai.com/tokenizer
2. [optional material] Hugging Face models to play with:
   1. [GPT2](https://huggingface.co/openai-community/gpt2)
   2. [BERT](https://huggingface.co/google-bert/bert-base-uncased)
   3. [RoBERTa](https://huggingface.co/FacebookAI/roberta-base)
   4. [ProtBert - BERT for proteins](https://huggingface.co/Rostlab/prot_bert)

### Activities

#### 1. Encoding fruits

- [teacher] teams of 2 - 3
- think about how should tokienizer encode individual words
- you have a vector of 5 integers, try to think about rules how to encode fruits into that vector (e.g. position 1 encodes color ...)
- get random fruit from neighbouring group and check if you can encode it
- let's think about a tuple of fruits that are (a) extremely similar (b) very dissimilar. Encode them and compute euclidian distance. Are they close / far?

#### 2. GPT tokenization

- have a look at this tokenization visualization: https://platform.openai.com/tokenizer
- think about different use-cases / texts for GPT and try to tokenize them
- is there anything that surprised you? Did you spot any potential problem? What is working well?

#### 3. Fill in one word

- [teacher] teams of 2 - 3
- ask students to prepare a shorter text (e.g. 3 - 5 sentences) and find one word, that is hard to guess if you don't have the full context but just one sentence / part of the sentence
- {Example: I watched the **weather** carefully. We wanted to go on a trip tomorrow and if there was a high chance of rain, we would probably cancel it.} 
- find other words in the text that have stronger relation to the chosen word and highlight them
- rewrite only small part of the text (one sentence) and mask the chosen word. Let other groups guess what should be there
- now give other groups the full text with highlighted context and let them guess again. Are they closer with the guess?

#### 4. [Optional activity]

- play a bit with some Hugging Face LLMs
- in Google Collab try to predict masked token with one of the models  
  
### Reasoning
- understand the importance of tokenization and how it can work
- highlight the importance of context

