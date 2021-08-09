# Level3-TextSummarization
Advanced submission for open source challenge, containing summarization and question answering. There are two parts to the project, the experimental notebook and notebook with UI components, both of which are explained down below.


<!-- UI -->

# Advanced TextSummarization(UI)

## Demo Video

Coming soon!

<!-- ABOUT THE PROJECT -->
## About The Project

Text summarization in NLP is the process of summarizing the information in large texts for quicker consumption. The intention is to create a coherent and fluent summary having only the main points outlined in the document. Question-Answering Models are machine or deep learning models that can answer questions given some context, and sometimes without any context. Automatic text summarization and question answering are common problems in machine learning and natural language processing (NLP). My project implements a UI. The user can input a link(preferrably and article or informative website), the question they want to ask about the text, and how many bullet points they want to be generated. Then from those parameters model generates a summary based on the raw text, bullet points, and the answered question.

Here are some resources to learn about text summarization, question answering, and the UI that I used:

* [A Quick Introduction to Text Summarization in Machine Learning](https://towardsdatascience.com/a-quick-introduction-to-text-summarization-in-machine-learning-3d27ccf18a9f)
* [Comprehensive Guide to Text Summarization using Deep Learning in Python](https://www.analyticsvidhya.com/blog/2019/06/comprehensive-guide-text-summarization-using-deep-learning-python/)
* [Text Summarization Approaches for NLP](https://www.machinelearningplus.com/nlp/text-summarization-approaches-nlp-example/)
* [Allen NLP](https://github.com/allenai/allennlp)
* [NLP — Building a Question Answering model](https://towardsdatascience.com/nlp-building-a-question-answering-model-ed0529a68c54)
* [Google AI Blog on Question Answering](https://ai.googleblog.com/2021/03/progress-and-challenges-in-long-form.html)
* [Gradio Getting Started](https://gradio.app/getting_started)
 

Results: 
* Input: *Check .ipynb*
* Output: *Check .ipynb*

### Built With

* [Transformers](https://huggingface.co)
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [NLTK](https://www.nltk.org)
* [AllenNLP](https://allennlp.org/)
* [Gradio](https://gradio.app/)

![](https://user-images.githubusercontent.com/36611240/128744426-cf5558fa-0933-481a-9f35-12787e91dda6.png)
![](https://user-images.githubusercontent.com/36611240/128744499-c5a22ff6-3c84-4e84-babf-c1de140574ba.png)



<!-- GETTING STARTED -->
## Getting Started

* *Clone git repository*
* *Make sure correct packages are installed(below)*
* *Run level3textsummarization.py*
* *or optionally for easier overall usage run Level3TextSummarization.ipynb in Google Colaboratory or Jupyter Notebook*
* *Go to https://13883.gradio.app/ in your browser*
* *Input all parameters and wait for summary and answers to be generated*

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* transformers:
  ```pip install transformers```
* NLTK:
  ```pip install nltk```
* BeautifulSoup:
  ```pip install bs4```
* Regular Expressions:
  ```pip install regex```
* HeapQ:
  ```pip install heapq```
* AllenNLP:
  ```pip install allennlp==1.0.0 allennlp-models==1.0.0```
* Gradio
 ```pip install gradio```


<!-- no UI -->

# Advanced TextSummarization(no UI)

## Demo Video

Coming soon!

<!-- ABOUT THE PROJECT -->
## About The Project

Text summarization in NLP is the process of summarizing the information in large texts for quicker consumption. The intention is to create a coherent and fluent summary having only the main points outlined in the document. Automatic text summarization is a common problem in machine learning and natural language processing (NLP). My project takes a link from a website(adjustable by user) and scrapes the raw text from the website. Then from this text my model generates a number of bullet points(adjustable by user) and a summary based on the raw text. Another feature that this project has is a question and answer feature. Question-Answering Models are machine or deep learning models that can answer questions given some context, and sometimes without any context. The model uses the scraped text from the website and takes a question as input which will then be answered by a transformer based model with relatively accurate results.

---
**NOTE**

The code works regardless of website or plain text as shown in demo video. Many customizable features are shown in demo video.

---


Here are some resources to learn about text summarization and question answering that I used:

* [A Quick Introduction to Text Summarization in Machine Learning](https://towardsdatascience.com/a-quick-introduction-to-text-summarization-in-machine-learning-3d27ccf18a9f)
* [Comprehensive Guide to Text Summarization using Deep Learning in Python](https://www.analyticsvidhya.com/blog/2019/06/comprehensive-guide-text-summarization-using-deep-learning-python/)
* [Text Summarization Approaches for NLP](https://www.machinelearningplus.com/nlp/text-summarization-approaches-nlp-example/)
* [Allen NLP](https://github.com/allenai/allennlp)
* [NLP — Building a Question Answering model](https://towardsdatascience.com/nlp-building-a-question-answering-model-ed0529a68c54)
* [Google AI Blog on Question Answering](https://ai.googleblog.com/2021/03/progress-and-challenges-in-long-form.html)
 

Results: 
* Input: *Check .ipynb*
* Output: *Check .ipynb*

### Built With

* [Transformers](https://huggingface.co)
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [NLTK](https://www.nltk.org)
* [AllenNLP](https://allennlp.org/)


<!-- GETTING STARTED -->
## Getting Started

* *Clone git repository*
* *Make sure correct packages are installed(below)*
* *Run level3textsummarization.py*
* *or optionally for easier overall usage run Level3TextSummarization.ipynb in Google Colaboratory or Jupyter Notebook*

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* transformers:
  ```pip install transformers```
* NLTK:
  ```pip install nltk```
* BeautifulSoup:
  ```pip install bs4```
* Regular Expressions:
  ```pip install regex```
* HeapQ:
  ```pip install heapq```
* AllenNLP:
  ```pip install allennlp==1.0.0 allennlp-models==1.0.0```


See the [open issues](https://github.com/NNDEV1/Level3-TextSummarization/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Nalin Nagar - nalinnagar1@gmail.com




