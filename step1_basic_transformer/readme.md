# PART 1: Introduction to the Transformer Architecture

Welcome to this notebook, where we will explore the inner workings of the revolutionary Transformer Architecture. 

Originally introduced in the paper "Attention is All You Need" by Vaswani et al. in 2017, transformers have become a cornerstone of modern Natural Language Processing (NLP) and have found applications in a myriad of other domains.

The transformer model, with its self-attention mechanism, is adept at handling sequences, making it perfect for tasks like translation, text generation, and more. Unlike recurrent models, transformers do not process data in order, which allows them to be more parallelizable and thus, faster to train on modern hardware.

In this notebook, our goal is to demystify the underlying components of the transformer architecture, specifically focusing on an autoregressive setting. By building it from scratch, we aim to provide clarity on how each part contributes to the overall functioning of the model.

In this notebook you will find one of the most complete documented code. My goal is to make sure you understand everything. We are not leaving any rock unturned here!

### Here's what we'll cover:

* Positional Encoding Class: Learn how transformers account for the order of data without inherently processing it sequentially.
* Scaled Dot Product Class: Dive into the self-attention mechanism and see how different parts of a sequence attend to each other.
* Attention Head Class: Understand the fundamental building block of the self-attention mechanism.
* Multi-head Attention Class: Discover how transformers harness multiple attention heads to capture various features from the data.
* Feed-forward Module Class: Delve into the feed-forward networks present within the transformer and their role.
* Transformer Block Class: See how the various components come together to form a transformer block.
* Transformer Model: Integrate the different classes to build the complete autoregressive transformer model.


By the end of this notebook, you'll have a hands-on understanding of the transformer architecture's components and the knowledge to build upon it for various applications. 

Whether you're a student, a researcher, or an enthusiast, this deep dive into transformers will equip you with the foundational knowledge to further explore the vast landscape of modern NLP.

##### Get ready for a lot of explanations!
