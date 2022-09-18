# Neural Re-ranking Tutorial (RecSys 22)

## Abstract
Re-ranking is one of the most critical stages for multi-stage recommender systems (MRS), which re-orders the input ranking lists by modeling the cross-item interaction. Recent re-ranking methods have evolved into deep neural architectures due to the significant advances in deep learning. Neural re-ranking, therefore, has become a trending topic and many of the improved algorithms have demonstrated their use in industrial applications, enjoying great commercial success. The purpose of this tutorial is to explore some of the recent work on neural re-ranking, integrating them into a broader picture and paving ways for more comprehensive solutions for future research. In particular, we provide a taxonomy of current methods according to the objectives and training signals. We examine and compare these methods qualitatively and quantitatively, and identify some open challenges and future prospects.

Our survey paper: [Neural Re-ranking in Multi-stage Recommender Systems: A Review](https://arxiv.org/pdf/2202.06602.pdf)

LibRerank re-ranking library: [https://github.com/LibRerank-Community/LibRerank](https://github.com/LibRerank-Community/LibRerank)

Tutorial slides: [[Slides]](slides-recsys22-tutorial-neuralreranking.pdf)

## Outline of the tutorial
* Introduction
    * Recommender system basics
    * Introduction to multi-stage recommender systems
    * Neural re-ranking fundamentals: challenges, objectives, network structures, and evaluations
* Single objective: Accuracy-oriented re-ranking
    * Learning by observed signals
    * Learning by counterfactual signals
    * Qualitative model comparison: network structure, optimization, personalization, and complexity
    * Quantitative comparison: LibRerank re-ranking library
* Multi-objective re-ranking
    * Diversity-aware re-ranking
    * Fairness-aware re-ranking
* Emerging applications 
* Summary and future prospects 

## Presenters
* [**Weiwen Liu**](https://wwliu555.github.io/). _Researcher, Huawei Noah’s Ark Lab_. She received her Ph.D. in Computer Science and Engineering from the Chinese University of Hong Kong in 2020. Her research is broadly concerned with ranking/re-ranking, recommender systems, information retrieval, and user preference learning.
* [**Jiarui Qin**](http://jiaruiqin.me/). _PhD student, Shanghai Jiao Tong University_. His research interests include data mining, machine learning, and information retrieval.
* [**Ruiming Tang**](https://scholar.google.com.sg/citations?user=fUtHww0AAAAJ&hl=en). _Lab director, Huawei Noah's Ark Lab_. His research interests include deep learning, reinforcement learning, ranking, AutoML, graph learning, and their applications in recommendation and search. He has published more than 70 papers in his interested research areas.
* [**Bo Chen**](https://scholar.google.com.sg/citations?user=RZU1wxsAAAAJ&hl=zh-CN). _Researcheer, Huawei Noah's Ark Lab_. He got his MS in Software Engineering from Shanghai Jiao Tong University in 2020. His research interests include recommender systems, ranking in computational advertising, deep learning, AutoML, and graph neural networks.




<!-- ## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/LibRerank-Community/neural-reranking-tutorial.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/LibRerank-Community/neural-reranking-tutorial.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
 -->
