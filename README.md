# GPT to Generate Graphs 

Can we tokenize graphs and train an autoregressive (AR) model with generative pre-trained transformers to generate graphs ? Even if auto-regressive models have superior performance on texts, diffusion, and flows have been the dominating paradigm for graph generative models. In this paper we revisit how to build AR models from generative pre-trained transformers for graph generation. 

*** 
**The key is tokenization!** To represent graphs as sequences, we tokenize graphs into node and edge sets. Building on this tokenization, we can adpot all existing recipes for generative pre-trained transformers in LLMs! We validate the quality of the learned embedding on graph property prediction problems and achieve better or on-par performance with other graph contrastive and generative pre-training methods. In the end, it's analyzed the scaling behaviour of Graph GPT and find on molecular graph representation, it scales very well with the data and model size and saturates when getting close to 100% validity. 
