# Task 6: Attention and Transformer Reflection

Text is composed of words that can be long-range, and RNNs work one word at a time which can be problematic. The longer the sequence, the earlier information may be more difficult for the model to remember.

LSTMs aid in memory by employing gates to determine what should be remembered, updated, or forgotten. This enables the model to retain important information for a longer time than a simple RNN.

Attention acts as a mechanism for models to remember which words are most critical in a given input sequence rather than paying attention to each word. It can be beneficial in certain applications such as summarisation, translation and text generation.

In NLP and Generative AI, transformers are crucial due to their implementation of attention mechanisms that allow for more efficient processing of words. While RNNs are limited to processing sequences one by one, transformers can process the entire sequence in parallel, leading to improved speed and ability to process longer text. Transformer architecture is the foundation for many current AI technologies, such as large language models and chatbots.