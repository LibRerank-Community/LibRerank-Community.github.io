<link rel="stylesheet" type="text/css" media="all" href="./my_style.css" />

# Neural Re-ranking Tutorial (RecSys 22)

## Abstract
Re-ranking is one of the most critical stages for multi-stage recommender systems (MRS), which re-orders the input ranking lists by modeling the cross-item interaction. Recent re-ranking methods have evolved into deep neural architectures due to the significant advances in deep learning. Neural re-ranking, therefore, has become a trending topic and many of the improved algorithms have demonstrated their use in industrial applications, enjoying great commercial success. The purpose of this tutorial is to explore some of the recent work on neural re-ranking, integrating them into a broader picture and paving ways for more comprehensive solutions for future research. In particular, we provide a taxonomy of current methods according to the objectives and training signals. We examine and compare these methods qualitatively and quantitatively, and identify some open challenges and future prospects.

Our survey paper: [Neural Re-ranking in Multi-stage Recommender Systems: A Review](https://arxiv.org/pdf/2202.06602.pdf)

LibRerank re-ranking library: [https://github.com/LibRerank-Community/LibRerank](https://github.com/LibRerank-Community/LibRerank)](https://github.com/LibRerank-Community/LibRerank)

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

<!DOCTYPE html>
<html>
<head>
<title>
	Wrapping an Image with the text
</title>
<style>
	body {
	margin: 20px;
	text-align: center;
	}

	h1 {
	color: green;
	}

	img {
	float: left;
	margin: 5px;
	}

	p {
	text-align: justify;
	font-size: 25px;
	}
</style>
</head>
<body>
<h1>GeeksforGeeks</h1>
<b>
	A Computer Science
	Portal for Geeks
</b>
<div class="square">
	<div>
	<img src="liuweiwen.jpg"
		alt="Longtail boat in Thailand">
	</div>
	
<p>
	How many times were you frustrated while looking
	out for a good collection of programming/algorithm
	/interview questions? What did you expect and what
	did you get? This portal has been created to
	provide well written, well thought and well
	explained solutions for selected questions.
	An IIT Roorkee alumnus and founder of GeeksforGeeks.
	He loves to solve programming problems in most
	efficient ways. Apart from GeeksforGeeks, he has
	worked with DE Shaw and Co. as a software developer
	and JIIT Noida as an assistant professor. It is a
	good platform to learn programming. It is an
	educational website. Prepare for the Recruitment
	drive of product based companies like Microsoft,
	Amazon, Adobe etc with a free online placement
	preparation course.
	</p>

</div>
</body>
</html>


<div class="square">
    <div>
      <img src="./liuweiwen.jpg" width="300" height="300"/>
    </div>
   <p>**Weiwen Liu.** _Researcher, Huawei Noah's Ark Lab._ She received her Ph.D. in Computer Science and Engineering from the Chinese University of Hong Kong in 2020. Her research is broadly concerned with ranking/re-ranking, recommender systems, information retrieval, and user preference learning. </p>
</div>

<div class="square">
    <div>
      <img src="./liuweiwen.jpg" width="300" height="300"/>
    </div>
   <p>**Weiwen Liu.** _Researcher, Huawei Noah's Ark Lab._ She received her Ph.D. in Computer Science and Engineering from the Chinese University of Hong Kong in 2020. Her research is broadly concerned with ranking/re-ranking, recommender systems, information retrieval, and user preference learning. </p>
</div>
<div class="square">
    <div>
      <img src="./liuweiwen.jpg" width="300" height="300"/>
    </div>
   <p>**Weiwen Liu.** _Researcher, Huawei Noah's Ark Lab._ She received her Ph.D. in Computer Science and Engineering from the Chinese University of Hong Kong in 2020. Her research is broadly concerned with ranking/re-ranking, recommender systems, information retrieval, and user preference learning. </p>
</div>
  

<img align="left" src="./liuweiwen.jpg" width="300" height="300"/>
<p style="text-align:left">**Weiwen Liu.** _Researcher, Huawei Noah's Ark Lab._ She received her Ph.D. in Computer Science and Engineering from the Chinese University of Hong Kong in 2020. Her research is broadly concerned with ranking/re-ranking, recommender systems, information retrieval, and user preference learning.</p>

<img align="left" src="./liuweiwen.jpg" width="300" height="300"/>
<p style="text-align:left">**Weiwen Liu.** _Researcher, Huawei Noah's Ark Lab._ She received her Ph.D. in Computer Science and Engineering from the Chinese University of Hong Kong in 2020. Her research is broadly concerned with ranking/re-ranking, recommender systems, information retrieval, and user preference learning.</p>


<img src="./liuweiwen.jpg" width="300" height="300"/>
<div style='vertical-align:middle; display:inline;'>
**Weiwen Liu.** _Researcher, Huawei Noah's Ark Lab._ She received her Ph.D. in Computer Science and Engineering from the Chinese University of Hong Kong in 2020. Her research is broadly concerned with ranking/re-ranking, recommender systems, information retrieval, and user preference learning.
</div>

<img src="./liuweiwen.jpg" width="300" height="300"/>
<div style='vertical-align:middle; display:inline;'>
**Weiwen Liu.** _Researcher, Huawei Noah's Ark Lab._ She received her Ph.D. in Computer Science and Engineering from the Chinese University of Hong Kong in 2020. Her research is broadly concerned with ranking/re-ranking, recommender systems, information retrieval, and user preference learning.
</div>

<p><img src="./liuweiwen.jpg" width="300" height="300"/>**Weiwen Liu.** _Researcher, Huawei Noah's Ark Lab._ She received her Ph.D. in Computer Science and Engineering from the Chinese University of Hong Kong in 2020. Her research is broadly concerned with ranking/re-ranking, recommender systems, information retrieval, and user preference learning.
</p>

<p><img src="./liuweiwen.jpg" width="300" height="300"/>**Weiwen Liu.** _Researcher, Huawei Noah's Ark Lab._ She received her Ph.D. in Computer Science and Engineering from the Chinese University of Hong Kong in 2020. Her research is broadly concerned with ranking/re-ranking, recommender systems, information retrieval, and user preference learning.
</p>

<div class="container">
<img src="./liuweiwen.jpg" width="300" height="300" align="left" />
**Weiwen Liu.** _Researcher, Huawei Noah's Ark Lab._ She received her Ph.D. in Computer Science and Engineering from the Chinese University of Hong Kong in 2020. Her research is broadly concerned with ranking/re-ranking, recommender systems, information retrieval, and user preference learning.
</div>

<div class="container">
<img src="./liuweiwen.jpg" width="300" height="300" align="left" />
**Weiwen Liu.** _Researcher, Huawei Noah's Ark Lab._ She received her Ph.D. in Computer Science and Engineering from the Chinese University of Hong Kong in 2020. Her research is broadly concerned with ranking/re-ranking, recommender systems, information retrieval, and user preference learning.
</div>


<img src="./qinjiarui.jpeg" width="300" height="300" align="left" />
*Jiarui Qin.** P_hD student, Shanghai Jiao Tong University._ His research interests include data mining, machine learning, and information retrieval.  <br><br><br><br><br><br><br><br><br><br><br><br><br>
<img src="./tangruiming.jpeg" width="300" height="300" align="left" />
**Ruiming Tang** Lab director, Huawei Noah's Ark Lab. His research interests include deep learning, reinforcement learning, ranking, AutoML, graph learning, and their applications in recommendation and search. He has published more than 70 papers in his interested research areas. <br><br><br><br><br><br><br><br><br><br><br><br><br>
<img src="./chenbo.jpeg" width="300" height="300" align="left" />  **Bo Chen** Researcheer, Huawei Noah's Ark Lab. He got his MS in Software Engineering from Shanghai Jiao Tong University in 2020. His research interests include recommender systems, ranking in computational advertising, deep learning, AutoML, and graph neural networks.
<br><br><br><br><br><br><br><br><br><br><br><br><br>



<!-- 
<img align="left" height="300px" width="300px" src="./qinjiarui.jpeg"/> &emsp;&emsp;&emsp;&emsp;<br>**Jiarui Qin.** P_hD student, Shanghai Jiao Tong University._ His research interests include data mining, machine learning, and information retrieval.</br>

<br>

<img align="left" height="300px" width="300px" src="./tangruiming.jpeg"/> **Ruiming Tang** Lab director, Huawei Noah's Ark Lab. His research interests include deep learning, reinforcement learning, ranking, AutoML, graph learning, and their applications in recommendation and search. He has published more than 70 papers in his interested research areas.

<br>

<img align="left" height="300px" width="300px" src="./chenbo.jpeg"/>  **Bo Chen** Researcheer, Huawei Noah's Ark Lab. He got his MS in Software Engineering from Shanghai Jiao Tong University in 2020. His research interests include recommender systems, ranking in computational advertising, deep learning, AutoML, and graph neural networks.  -->

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
