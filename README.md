# Linformer

## Group Members
Tara Amruthur, Anna Arantes, Jesse Edelstein, Marie Baker

## Project Overview
Transformer models are a very popular deep learning architecture used across several natural language processing (NLP) tasks, such as classification and text translation. However, these models are substantial in size and require considerable computational resources and time for training. Wang et al. introduce an alternative architecture, the Linformer, that addresses this predicament by modifying the self attention mechanism: unlike traditional Transformer models that calculate attention with quadratic complexity, i.e. O(n2), the Linformer operates with linear complexity, significantly reducing computational load and processing time. Though the original Linformer paper highlights the benefits of using the Linformer model on different text-based tasks, mainly focused on its efficiency compared to the traditional Transformer models, they have only applied the model on datasets related to movie reviews, particularly the IMDB reviews dataset and the SST-2 dataset (a dataset consisting of one-sentence snippets of movie reviews). Thus, to address this limitation, we decided to test the Linformer on a wider, more diverse dataset: an Amazon reviews set. The goal was to assess the Linformer’s adaptability and performance across a more varied range of content. In addition, we investigated the impact of hyperparameters including the compression ratio, shared KV, and shared layer KV.

## Link
Example checkpoint created: https://drive.google.com/file/d/1L52rfRpmpIZ7-JTZAj78QAaxmDCj561f/view
