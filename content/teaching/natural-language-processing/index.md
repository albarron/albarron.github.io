---
title: Natural Language Processing
summary: The TraTec NLP course
date: 2024-10-29
type: docs
math: true
tags:
  - NLP
image:
  caption: 'The Natural Language Processing lesson at DIT'
---

**Academic Year 2024/2025**

(frontpage illustration produced with 
[deepai's tool](https://deepai.org/machine-learning-model/text2img) in October 2024; using prompt 
_natural language processing class for translation and technology masters_).

Visit the [UniBO website of the lecture](https://www.unibo.it/it/studiare/dottorati-master-specializzazioni-e-altra-formazione/insegnamenti/insegnamento/2024/470093) for official and administrative details.

## Prerequisites

### A gentle introduction to [Python](https://www.python.org/) {#topic0}
This topic **wont be covered in class**.

```
if you are a student of TraTec:
  you had the intro to Python in PBR
elif you are a student of SpecTra:
  you had the intro to python in APS
else: 
  check the slides, notebooks, and 2021 video recordings
```

Regardless, you can find the materials on [virtuale](https://virtuale.unibo.it/). 
<!-- [https://github.com/TinfFoil/learning_dit_python](https://github.com/TinfFoil/learning_dit_python) (**as of June 24 the link is not working yet**).  -->

Regardless of whether you attended either of the introductions, I suggest you to **do (or re-visit) all the exercises ASAP**.


## Homework

Homework is going to be handled through 
[virtuale](https://virtuale.unibo.it/course/view.php?id=64197). No further 
contents are expected to be shared there. On 09/10, you should have obtained 
the password to access from me. If you did not, ping me. Homework has 
associated a hard deadline.

## Course contents

Whereas the contents could be (slightly) adapted according to the students skills and interests, the general structure of the course is as follows.

### 1. Introduction to Natural Language Processing

- MO 30/09/24 [Slides](/uploads/nlp24/01_dit_nlp_handout.pdf)

### 2. Words and the vector space model

- WE 02/10/24 [Slides on tokens](/uploads/nlp24/02_dit_nlp_handout.pdf) 
- WE 03/10/24 [Notebook on tokens and normalisation](/uploads/nlp24/02_dit_nlp_words.ipynb)
- WE 09/10/24 [Slides on VSM](/uploads/nlp24/03_dit_nlp_handout.pdf)
- WE 09/10/24 [Notebook on VSM](/uploads/nlp24/03_dit_nlp_tokens.ipynb)

### 3. Rule-based and Naïve Bayes
- TH 10/10/24 [Slides on RB sentiment (+ naive bayes)](/uploads/nlp24/04_dit_nlp_handout.pdf) 
- TH 10/10/24 [Notebook on RB sentiment](/uploads/nlp24/04_dit_nlp_rulebasedsentiment.ipynb) 
- WE 16/10/24  [Notebook on Naïve Bayes](/uploads/nlp24/05_dit_nlp_naivebayes.ipynb)

### 4. Word vectors
- TH 17/10/24 [Slides on tf-idf](/uploads/nlp24/06_dit_nlp_handout.pdf)
- ~~TH 17/10/24~~ WE 23/10/24 [Notebook](/uploads/nlp24/06_dit_nlp_tf_idf.ipynb)
 

### 5. From Word Counts to Meaning

- ~~WE 23/10/24~~ TH 24/10/24 [Slides introducing topic modelling](/uploads/nlp24/07_dit_nlp_handout.pdf)
- ~~WE 23/10/23~~ TH 24/10/24 [Notebook on topic modelling](/uploads/nlp24/07_dit_nlp_topicmodeling.ipynb) 
<!-- THIS LESSON WAS NOT OFFERED IN  2024
- 24/10/23 [Slides introducing LSA and SVD](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_04/08_dit_nlp_handout.pdf)
- 24/10/23 [Notebook on LSA](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_04/08_dit_nlp_lsa.ipynb) -->

### 6. Training and Evaluation
- 30/10/23 [Slides on training and evaluation](/uploads/nlp24/09_dit_nlp_handout.pdf)
- 30/10/23 [Notebook](/uploads/nlp24/09_dit_nlp_traineval.ipynb)

### 7. Intro to NN
- 31/10/23 [Slides](/uploads/nlp24/10_dit_nlp_handout.pdf) on the perceptron
- 31/10/23 [Notebook](/uploads/nlp24/10_dit_nlp_nn.ipynb) on the 
perceptron

**Intermezzo**

- 13/11/23 [Slides](/uploads/nlp24/11_dit_nlp_handout.pdf) introducing neural networks and keras
- 13/11/23 [Notebook](/uploads/nlp24/11_dit_nlp_keras.ipynb)

### 8. Word Embeddings
- 14/11/24 [Slides](/uploads/nlp24/12_dit_nlp_handout.pdf) on word2vec
- 18/11/24 [Slides](/uploads/nlp24/13_dit_nlp_handout.pdf) hands on word 
embeddings
- 18/11/24 [Notebook](/uploads/nlp24/13_dit_nlp_embeddings.ipynb)
  

### 9. Doc2Vec
- 14/11/23 [Slides](/uploads/nlp24/14_dit_nlp_handout.pdf)
- 14/11/23 [Notebook](/uploads/nlp24/14_dit_nlp_d2v.ipynb)
<!-- - 14/11/23 [Project reminder](/uploads/nlp24/14_dit_nlp_projects.pdf) -->

<!-- THIS WAS NOT GIVEN SINCE TWO YEARS AGO
### 10. Visualisation
  I have decided not to offer this lecture anymore
* \[13/04/22\] Slides on visualization
* \[13/04/22\] Notebook
 -->

### 10. Convolutions for  text
- 27/11/24 [Slides](/uploads/nlp24/15_dit_nlp_handout.pdf)
<!-- - 20/11/23 [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_08/15_dit_nlp_cnn.ipynb) -->


### 11. Text is Sequential / LSTM
<!-- - 21/11/23 [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_08/16_dit_nlp_handout.pdf) on RNN
- 21/11/23 [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_08/16_dit_nlp_rnn.ipynb) on  RNN
- 27/11/23 [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_09/17_dit_nlp_handout.pdf) on BiRNN and LSTM
- 27/11/23 [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_09/17_dit_nlp_brnn.ipynb) on BiRNN 
- 27/11/23 [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_09/17_dit_nlp_lstm.ipynb) on LSTM -->

### 12. Text generation
<!-- - 28/11/23 [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_09/18_dit_nlp_handout.pdf) on characters and generation
- 28/12/23 [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_09/18_dit_nlp_chars.ipynb) on characters
- 28/12/23 [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_09/18_dit_nlp_lstm-gen.ipynb) on generation
 -->
<!-----
**The topics/timing from here are indicative and subject to (continuous) 
modification**
----->
### ~~13. Intro to Seq2Seq and Transformers ; Closing Remaks~~

<!-- ~~- 05/12/23 [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_10/19_dit_nlp_handout.pdf) for part one~~ -->

### 13. A brief intro to LLMs

<!-- - 11/12/23 [CLIC-it 2023 tutorial](https://github.com/crux82/CLiC-it_2023_tutorial) (we will pay a visit to the cool materials from D. Croce and C.D. Hromei) -->



## Calendars 

Table 1 shows the calendar for the 20 NLP lessons.

This year, NLP has two _sibling_ lessons:

- Selected Topics in Natural Language Processing is an optional (with credits). Further information about it is available on the [UniBO website](https://www.unibo.it/it/studiare/dottorati-master-specializzazioni-e-altra-formazione/insegnamenti/insegnamento/2024/508809). Table 2 shows the calendar of the 8 lessons.
- Tutorato of NLP is made to support **you** in the programming side of NLP. Table 3 shows the calendar of the 10 lessons.

{{< table path="calendar_nlp.csv" header="true" caption="Table 1: Calendar overviewing all 20 NLP planned lessons." >}}

{{< table path="calendar_selnlp.csv" header="true" caption="Table 2: Calendar overviewing all 8 Selected Topics in NLP planned lessons." >}}

(1) ImprenDITori di se stessi. TH aula 10

{{< table path="calendar_tutorato.csv" header="true" caption="Table 3: Calendar overviewing all 10 NLP _tutorato_." >}}


## <a id="projects"></a>Projects

For your final mark, [80% comes from the final project](https://www.unibo.it/it/studiare/dottorati-master-specializzazioni-e-altra-formazione/insegnamenti/insegnamento/2024/470093). Look for inspiration, in the [projects presented in previous years](#nlp_projects)

### Some project ideas

Eventually, I will drop here some ideas for final projects.

## Previous final projects {#nlp_projects}

### 2024-2025

_yours will be here_

### 2023-2024

* Cupin E., Galiero L., and Ciminari D. (2023).
  Back to the Roots: Tracing Source Languages in Wikipedia with LABSE<br />
  [🗎](/uploads/nlp23/dit_nlp23_finalproject_Cupin_Ciminari_Galiero.pdf)
### 2022-2023

* Mainardi. P (2023).
  Identifying masculine generics in Italian<br />
  [🗎](/uploads/nlp23/dit_nlp23_finalproject_Mainardi.pdf)

### 2021-2022

* Gajo, P. (2022). 
Hate Speech Detection in Incel Online Spaces<br />
[🗎](https://github.com/albarron/academic-kickstart/raw/master/files/coli/projects2022/dit_coli2022_project_gajo.pdf) 
  
* Kovacs, M. (2022).
 Fishing for catfishes: using a model trained on Twitter data to predict author gender in Reddit posts<br />
  [🗎](https://github.com/albarron/academic-kickstart/raw/master/files/coli/projects2022/dit_coli2022_project_kovacs.pdf)

### 2020-2021

* Hopkins, D. (2022). Assessing Semantic Similarity between Original Texts and Machine Translations<br />
  [🗎](https://github.com/albarron/academic-kickstart/raw/master/files/coli/projects2021/dit_coli2021_project_hopkins.pdf)
  
<!-- * Martinelli, M. (2021). Definition extraction on food-related Wikipedia articles -->
  
* Galletti, E. (2021). Identifying Characters’ Lines in Original and Translated Plays. The case of Golden and Horan’s Class<br />
  [🗎](https://github.com/albarron/academic-kickstart/raw/master/files/coli/projects2020/dit_coli2020_project_galletti.pdf)

* Yu, X. (2021). Classifying An Imbalanced Dataset with CNN, RNN, and LSTM<br />
  [🗎](https://github.com/albarron/academic-kickstart/raw/master/files/coli/projects2020/dit_coli2020_project_yu.pdf)

### 2019-2020

* Fernicola F. and Zhang S. (2020). 
  AriEmozione: Identifying Emotions in Opera Verses<br />
  (developed under [CRICC](https://site.unibo.it/cricc/it);
  published in [CLiC-it 2020](http://ceur-ws.org/Vol-2769/))<br />
  [🗎](http://ceur-ws.org/Vol-2769/paper_58.pdf)
  [🎦](https://vimeo.com/515280902)

* Muti, A. (2020).
  UniBO@AMI: A Multi-Class Approach to Misogyny and Aggressiveness
  Identification on Twitter Posts Using AlBERTo<br />
  (top-performing model in [Evalita's 2020
  AMI](https://amievalita2020.github.io/) shared task)<br />
  [🗎](http://ceur-ws.org/Vol-2765/paper117.pdf) 
  [🎦](https://vimeo.com/487827751)
<!-- **Embed videos, podcasts, code, LaTeX math, and even test students!**

On this page, you'll find some examples of the types of technical content that can be rendered with Hugo Blox.
 -->
<!-- ## Video

Teach your course by sharing videos with your students. Choose from one of the following approaches:

{{< youtube D2vj0WcvH5c >}}

**Youtube**:

    {{</* youtube w7Ft2ymGmfc */>}}

**Bilibili**:

    {{</* bilibili id="BV1WV4y1r7DF" */>}}

**Video file**

Videos may be added to a page by either placing them in your `assets/media/` media library or in your [page's folder](https://gohugo.io/content-management/page-bundles/), and then embedding them with the _video_ shortcode:

    {{</* video src="my_video.mp4" controls="yes" */>}}

## Podcast

You can add a podcast or music to a page by placing the MP3 file in the page's folder or the media library folder and then embedding the audio on your page with the _audio_ shortcode:

    {{</* audio src="ambient-piano.mp3" */>}}

Try it out:

{{< audio src="ambient-piano.mp3" >}}

## Test students

Provide a simple yet fun self-assessment by revealing the solutions to challenges with the `spoiler` shortcode:

```markdown
{{</* spoiler text="👉 Click to view the solution" */>}}
You found me!
{{</* /spoiler */>}}
```

renders as

{{< spoiler text="👉 Click to view the solution" >}} You found me 🎉 {{< /spoiler >}}

## Math

Hugo Blox Builder supports a Markdown extension for $\LaTeX$ math. You can enable this feature by toggling the `math` option in your `config/_default/params.yaml` file.

To render _inline_ or _block_ math, wrap your LaTeX math with `{{</* math */>}}$...${{</* /math */>}}` or `{{</* math */>}}$$...$${{</* /math */>}}`, respectively.

{{% callout note %}}
We wrap the LaTeX math in the Hugo Blox _math_ shortcode to prevent Hugo rendering our math as Markdown.
{{% /callout %}}

Example **math block**:

```latex
{{</* math */>}}
$$
\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}
$$
{{</* /math */>}}
```

renders as

{{< math >}}
$$\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}$$
{{< /math >}}

Example **inline math** `{{</* math */>}}$\nabla F(\mathbf{x}_{n})${{</* /math */>}}` renders as {{< math >}}$\nabla F(\mathbf{x}_{n})${{< /math >}}.

Example **multi-line math** using the math linebreak (`\\`):

```latex
{{</* math */>}}
$$f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}$$
{{</* /math */>}}
```

renders as

{{< math >}}

$$
f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}
$$

{{< /math >}}

## Code

Hugo Blox Builder utilises Hugo's Markdown extension for highlighting code syntax. The code theme can be selected in the `config/_default/params.yaml` file.


    ```python
    import pandas as pd
    data = pd.read_csv("data.csv")
    data.head()
    ```

renders as

```python
import pandas as pd
data = pd.read_csv("data.csv")
data.head()
```

## Inline Images

```go
{{</* icon name="python" */>}} Python
```

renders as

{{< icon name="python" >}} Python

## Did you find this page helpful? Consider sharing it 🙌
 -->
