## Educational Summary: Fibonacci Neural Networks

---



This project explores a novel neural network architecture inspired by the Fibonacci sequence, a series of numbers where each number is the sum of the two preceding ones (e.g., 0, 1, 1, 2, 3, 5, 8...).

**What are Fibonacci Neural Networks (FNNs)?**

Unlike traditional neural networks that have layers of fully connected neurons or specific connection patterns (like in Convolutional Neural Networks or Recurrent Neural Networks), FNNs use a connection structure based on the Fibonacci sequence. This means that neurons are connected according to this recursive pattern, creating a unique, non-layered network topology.

**Why explore FNNs?**

The idea behind FNNs is to investigate if this recursive, self-referential structure, found in various natural phenomena, can offer advantages in artificial intelligence, potentially mimicking aspects of biological intelligence and leading to more efficient learning or novel forms of information processing.

**Experiments Conducted:**

1.  **Image Classification (Fashion MNIST):** An FNN was built and trained on the Fashion MNIST dataset to classify images of clothing. The results showed that the FNN was able to learn effectively, reducing loss and increasing accuracy over time, demonstrating its capability in visual pattern recognition.

2.  **Natural Language Processing (IMDB Sentiment Analysis):** To test the generalizability of FNNs, the architecture was applied to a text classification task using the IMDB Sentiment Analysis dataset. The network, using GloVe word embeddings to represent text, successfully learned to classify movie reviews as positive or negative, indicating its potential in processing sequential data like text.

**Key Findings:**

*   Fibonacci-based connectivity is a viable alternative to traditional layered network structures.
*   The FNN architecture can successfully learn and perform on both image and text-based tasks.
*   The recursive nature of FNNs might offer unique computational properties and open up new avenues for biologically inspired AI research.

**Further Exploration:**

The project suggests further research is needed to:

*   Evaluate FNNs on more complex datasets.
*   Understand how the performance of FNNs scales with network size.
*   Analyze the potential energy efficiency benefits of this architecture.

This project provides a foundational step in understanding the capabilities of neural networks with non-traditional, biologically inspired connectivity patterns like those based on the Fibonacci sequence.
