# CrossNLI
Repository for the paper "LLMs Struggle with NLI for Perfect Aspect: A Cross-Linguistic Study in Chinese and Japanese"
Author: Jie Lu, Du Jin, Hitomi Yanaka

# About the paper(Paper Abstract)
Unlike English, which uses distinct forms (e.g., had/has/will have) to mark the perfect aspect across tenses, Chinese and Japanese lack separate grammatical forms for tense within the perfect aspect, which complicates natural language inference (NLI).
Focusing on the perfect aspect in these languages, we construct a linguistically motivated, template-based NLI dataset (1,350 pairs per language). 
Experiments reveal that even advanced LLMs struggle with temporal inference, particularly in detecting subtle tense and reference-time shifts. 
These findings highlight model limitations and underscore the need for cross-linguistic evaluation in temporal semantics.

# About the dataset
All template and variables we used in our paper are in file "Templates_chinese.xlsx" and "Templates_japanese.xlsx".
This Excel file is composed of two sheets: Templates and Variables, each serving a specific role in the context of linguistic data processing or natural language inference (NLI) research.

## Sheet: Templates
Description: This sheet contains a structured dataset of sentence pairs labeled for semantic relationships. It is likely intended for use in tasks such as Natural Language Inference (NLI), sentence similarity evaluation, or linguistic pattern analysis. 
Each row represents a single data instance with the following columns:
  - number: A unique identifier or index for each row.

  - premise: The original sentence, serving as the base for inference.

  - hypothesis: A second sentence compared with the premise to assess logical or semantic relation.

  - label: The annotated relationship between the premise and the hypothesis (e.g., entailment, contradiction, neutral).

  - example1: An example sentence related to the premise or hypothesis to illustrate usage or context.

  - example2: A second example sentence, possibly contrasting with example1.

  - premise_cate: A categorical tag indicating the type or class of the premise sentence.

  - hypothesis_cate: A categorical tag indicating the type or class of the hypothesis sentence.

## Sheet: Variables
Description: This sheet contains a list of Japanese lexical items that function as variables in the sentence templates. These variables may be used to dynamically generate or modify sentences in the Templates sheet, facilitating controlled experimentation or linguistic variation.

  - variables_japanese(chinese): A list of Japanese words or phrases used as placeholders or substitution elements in template-based sentence generation.


# Citation
If you use this dataset and code in any published research, please cite the following paper: 
- Jie Lu, Du Jin, Hitomi Yanaka, LLMs Struggle with NLI for Perfect Aspect: A Cross-Linguistic Study in Chinese and Japanese, Proceedings of the 16th International Conference on Computational Semantics, 2025.

<pre><code>```
@InProceedings{jie-2025-crossNLI,
  author    = {Jie, Lu and Du, Jin and Hitomi, Yanaka},
  title     = {LLMs Struggle with NLI for Perfect Aspect: A Cross-Linguistic Study in Chinese and Japanese},
  booktitle = {Proceedings of the 16th International Conference on Computational Semantics},
  year      = {2025},
}
``` </code></pre>

# Contact
For questions and usage issues, please contact lujie2001yoshino@gmail.com.

# License

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

