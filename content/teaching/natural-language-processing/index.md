---
title: Natural Language Processing
summary: The TraTec NLP course
date: 2026-09-25
type: docs
math: true
tags:
  - NLP
image:
  caption: 'The Natural Language Processing lesson at DIT'
---

**Academic Year 2026/2027**

(frontpage illustration produced with 
[deepai's tool](https://deepai.org/machine-learning-model/text2img) in October 2024; using prompt 
_natural language processing class for translation and technology masters_).

Visit the [UniBO website of the lecture](https://www.unibo.it/en/study/course-units-transferable-skills-moocs/course-unit-catalogue/course-unit/2026/532362) for official and administrative details.

## Prerequisites

### A gentle introduction to [Python](https://www.python.org/) {#topic0}
This topic **wont be covered in class**.

```
if you are a student of TraTec:
  you had the intro to Python in PBR
elif you are a student of SpecTra:
  you had the intro to python in APS
```

<!-- Regardless, you can find the materials on [virtuale](https://virtuale.unibo.it/). 
 [https://github.com/TinfFoil/learning_dit_python](https://github.com/TinfFoil/learning_dit_python) (**as of June 24 the link is not working yet**).  -->

Regardless of whether you attended either of the introductions, I suggest you to **do (or re-visit) all the exercises ASAP**.


## Homework

Homework is going to be handled through 
[virtuale](https://virtuale.unibo.it/course/view.php?id=75804). No further 
contents are expected to be shared there. By 30th September, you should obtained 
the password to access from me. If you did not, ping me. Homework has 
associated a hard deadline.

## Course contents

Whereas the contents could be (slightly) adapted according to the students skills and interests, the general structure of the course is as follows.

Lessons with a star (\*) are tentative.

### 1. Introduction to Natural Language Processing

- Lesson 1. MO 28/09/26 [Slides](/uploads/nlp/01_dit_nlp_handout.pdf) Introduction

### 2. Words and the vector space model

- Lesson 2. WE 30/09/26 [Slides](/uploads/nlp/02_dit_nlp_handout.pdf) Tokens and normalisation
- Lesson 2. WE 30/10/26 [Notebook](/uploads/nlp/02_dit_nlp_words.ipynb) Tokens and normalisation
- Lesson 3. MO 05/10/26 [Slides](/uploads/nlp/03_dit_nlp_handout.pdf) Vector Space Model
- Lesson 3. MO 05/10/26  [Notebook](/uploads/nlp/03_dit_nlp_tokens.ipynb) Vector Space Model

### 3. Rule-based and Naïve Bayes' classifier

- Lesson 4. WE 07/10/26 Rule-based sentiment analysis [Slides](/uploads/nlp/04_dit_nlp_handout.pdf)
- Lesson 4. WE 07/10/26 [Notebook](/uploads/nlp/04_dit_nlp_rulebasedsentiment.ipynb)
Rule-based sentiment analysis

- Lesson 5. MO 12/10/26 Naïve Bayes' classifier
<!-- [Slides](/uploads/nlp/05_dit_nlp_handout.pdf)  -->
<!-- - Lesson 5. MO 12/10/26  -->
<!-- [Notebook](/uploads/nlp/05_dit_nlp_naivebayes.ipynb)  -->
<!-- Naïve Bayes' classifier  -->


### 4. Word vectors
- Lesson 6. WE 14/10/26 Term Frequency–Inverse Document Frequency
<!-- [Slides](/uploads/nlp/06_dit_nlp_handout.pdf)  -->
- Lesson 7. MO 19/10/26 Term Frequency–Inverse Document Frequency
<!-- [Notebook](/uploads/nlp/06_dit_nlp_tf_idf.ipynb)  -->

<!-- 
- ~~TH 17/10/26~~ 
-->

### 5. From Word Counts to Meaning

- Lesson 8. WE 21/10/26 [Slides] From word counts to meaning (introducing topic modelling)
<!-- (/uploads/nlp/08_dit_nlp_handout.pdf)  -->
<!-- - Lesson 8. WE 21/10/26  -->
<!-- [Notebook](/uploads/nlp/08_dit_nlp_topicmodeling.ipynb)  -->
<!-- From word counts to meaning (introducing topic modelling)  -->

<!-- - ~~WE 23/10/26~~ TH 24/10/26 -->

<!-- THIS LESSON WAS NOT OFFERED IN  2024-->
- Lesson 9. MO 26/10/26  Introduction to LSA and SVD\*
<!-- [Slides](https://github.com/albarron/academic-kickstart/raw/master/files/nlp23/week_04/08_dit_nlp_handout.pdf) -->
<!-- - Lesson 9. MO 26/10/26  -->
<!-- [Notebook](https://github.com/albarron/academic-kickstart/blob/master/files/nlp23/week_04/08_dit_nlp_lsa.ipynb)  -->
<!-- Introduction to LSA and SVD\* -->


### 6. Training and Evaluation
- Lesson 10. WE 28/10/26 Training and evaluation
<!-- [Slides](/uploads/nlp/09_dit_nlp_handout.pdf)  -->
<!-- - Lesson 10. WE 28/10/26  -->
<!-- [Notebook](/uploads/nlp/09_dit_nlp_traineval.ipynb)  -->
<!-- Training and evaluation -->

### 7. Intro to NN
- Lesson 11. MO 02/11/26 
<!-- [Slides](/uploads/nlp/10_dit_nlp_handout.pdf)  -->
<!-- - Lesson 11. MO 02/11/26  -->
<!-- [Notebook](/uploads/nlp/10_dit_nlp_nn.ipynb) -->
<!-- One  neuron (the perceptron) -->
<!-- **Intermezzo** -->
- Lesson 12. WE 04/11/26 Neural networks and keras
<!-- [Slides](/uploads/nlp/11_dit_nlp_handout.pdf)  -->
<!-- - Lesson 12. WE 04/11/26  -->
<!-- [Notebook](/uploads/nlp/11_dit_nlp_keras.ipynb)  -->
<!-- Neural networks and keras -->

### 8. Word Embeddings
- Lesson 13. MO 09/11/26 Word2vec
<!-- [Slides](/uploads/nlp/12_dit_nlp_handout.pdf)  -->
- Lesson 14. WE 11/11/26 Hands on word embeddings
<!-- [Slides](/uploads/nlp/13_dit_nlp_handout.pdf)  -->
<!-- - Lesson 14. WE 11/11/26  -->
<!-- [Notebook](/uploads/nlp/13_dit_nlp_embeddings.ipynb)  -->
<!-- Hands on word embeddings -->

### 9. Doc2Vec
- Lesson 15. MO 16/11/26 From word back to document representations (doc2vec)
<!-- [Slides](/uploads/nlp/14_dit_nlp_handout.pdf)  -->
<!-- - Lesson 15. MO 16/11/26  -->
<!-- [Notebook](/uploads/nlp/14_dit_nlp_d2v.ipynb)  -->
<!-- From word back to document representations (doc2vec)  -->
<!-- - 14/11/23 [Project reminder](/uploads/nlp/14_dit_nlp_projects.pdf) -->

<!-- THIS WAS NOT GIVEN SINCE TWO YEARS AGO -->
### 10. Visualisation*
  <!-- I have decided not to offer this lecture anymore -->
- Lesson 16. WE 18/11/26 Visualisation
<!-- - Lesson 16. WE 18/11/26
* \[13/04/22\] Slides on visualization
* \[13/04/22\] Notebook
 -->
### 11. Convolutions for  text
- Lesson 17. MO 23/11/26 CNNs
<!-- [Slides](/uploads/nlp/15_dit_nlp_handout.pdf)  -->
- Lesson 18. WE 25/11/26 CNNs
<!-- [Notebook](/uploads/nlp/15_dit_nlp_cnn.ipynb)  -->

(big thanks to P. Gajo for helping with making the notebooks more 
memory-efficient)

### 11. Text is Sequential / LSTM
- Lesson 19. MO 30/11/26 RNNs
<!-- [Slides](/uploads/nlp/17_dit_nlp_handout.pdf)  -->
<!-- - Lesson 19. MO 30/11/26  -->
<!-- [Notebook](/uploads/nlp/17_dit_nlp_rnn.ipynb)  -->
<!-- RNNs -->
- Lesson 20. WE 02/12/26 BiRNNs and LSTMs
<!-- [Slides](/uploads/nlp/18_dit_nlp_handout.pdf)  -->
<!-- - Lesson 20. WE 02/12/26  -->
<!-- [Notebook](/uploads/nlp/18_dit_nlp_brnn.ipynb)  -->
<!-- BiRNNs -->
- Lesson 21? LSTMs\*
<!-- . 26/11/26  -->
<!-- [Notebook](/uploads/nlp/18_dit_nlp_lstm.ipynb)  -->



<!-- ### - CLIC-it 2024 -->
<!-- - [Poster 1](/uploads/nlp25/clic24_eptic.pdf) Constructing a Multimodal, 
Multilingual Translation
and Interpreting Corpus: A Modular Pipeline and an Evaluation of ASR for 
Verbatim Transcription
- [Poster 2](/uploads/nlp25/clic24_projection.pdf) On Cross-Language Entity 
Label Projection and Recognition -->

### 12. Text generation*
<!--- Lesson 19. 01/12/26  
 [Slides](/uploads/nlp/19_dit_nlp_handout.pdf)  
LSTM: 
characters and generation
- Lesson 19. 01/12/26 
[Notebook](/uploads/nlp/19_dit_nlp_chars.ipynb) 
LSTM: 
characters
- Lesson 19. 01/12/26 
[Notebook](/uploads/nlp/19_dit_nlp_lstm_gen.ipynb) 
LSTM: 
generation
-->

<!-- ### 13. Closing

- Lesson 20. 10/12/26 
[Slides](/uploads/nlp/20_dit_nlp_handout.pdf) 
Closing
- Lesson 20. 10/12/26 
[Notebook](/uploads/nlp/20_dit_nlp_shakes.ipynb) 
Pre-trained LSTM: generation. 
- Lesson 20. 10/12/26 --> 
<!-- [Model structure](/uploads/nlp/shakes_lstm_model.json) 
and the weights (as trained during lesson 19) after 
[1](/uploads/nlp/shakes_lstm_1.weights.h5),
[2](/uploads/nlp/shakes_lstm_2.weights.h5), 
[3](/uploads/nlp/shakes_lstm_3.weights.h5), 
[4](/uploads/nlp/shakes_lstm_4.weights.h5), and 
[5](/uploads/nlp/shakes_lstm_5.weights.h5) epochs.
 -->
<!-- (the students preferred a Q&A over Seq2Seq and transformers) -->
<!-----
**The topics/timing from here are indicative and subject to (continuous) 
modification**

### 13. Intro to Seq2Seq and Transformers
Lesson 20 10/12/25-->
<!-- - 16/12/24 [Slides](/uploads/nlp/19_dit_nlp_handout.pdf) 20. Into 
Transformers
- 16/12/24 [Slides](/uploads/nlp/20_dit_nlp_handout.pdf) 20. Beyond; 
[attention gif](/uploads/nlp/transform20fps.gif) -->

<!-- ### 14. A brief intro to LLMs + Closing Remaks -->

<!-- This section was not covered during the lesson and was left for furher studying 

- [CLIC-it 2023 tutorial](https://github.com/crux82/CLiC-it_2023_tutorial) (we will pay a visit to the cool materials from D. Croce and C.D. Hromei)
 -->
### FIN

## Selected topics in NLP

From this year, NLP has one _follow-up_ lesson:

- Selected Topics in Natural Language Processing is an optional (with credits). 
Further information about it is available on the [UniBO 
website](https://www.unibo.it/it/studiare/insegnamenti-competenze-trasversali-moocs/insegnamenti/insegnamento/2026/532447). 
<!-- Table 1 shows the calendar of the 8 lessons. -->

<!-- {{< table path="calendar_selnlp.csv" header="true" caption="Table 1: Calendar overviewing all 8 Selected Topics in NLP planned lessons." >}} -->
<!--
- Tutorato of NLP is made to support **you** in the programming side of NLP. 
Table 3 shows the calendar of the 10 lessons.
-->


## <a id="projects"></a>Projects

For your final mark, [80% comes from the final project](https://www.unibo.it/it/studiare/insegnamenti-competenze-trasversali-moocs/insegnamenti/insegnamento/2025/470093). Look for inspiration, in the [projects presented in previous years](#nlp_projects)

### Some project ideas

- Given an entry from a restaurant menu, split into name, description, and 
price.
- Participate to the EVALITA [shared task on detecting and classifying gender stereotypes in Italian](https://gsi-d-evalita.fbk.eu)

Eventually, I will drop here more ideas for final projects.

## Previous final projects {#nlp_projects}

### 2026-2027

_yours will be here_

### 2025-2026

_to be updated_

### 2024-2025

* Santangelo D.P. (2025)
  No Stupid Questions, Only Labeled Ones: Intent Classification for University 
  FAQs
  <br />
  [🗎](/uploads/nlp25/dit_nlp25_finalproject_Santangelo.pdf)

* Forzatti A. (2025)
  Benchmarking Bilingual Text Anonymization and Automatic Term Extraction Approaches<br />
  [🗎](/uploads/nlp25/dit_nlp25_finalproject_Forzatti.pdf)

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
