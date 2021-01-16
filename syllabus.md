## COMM313: Computational Text Analysis for Communication Research
**Spring 2021: Tu/Th 12.00-1.30pm**  


**Professor**: Dr. Matt O'Donnell (he/him/his)
**Email**: mbod@asc.upenn.edu

**TA**: Jake Parelman (he/him/his)
**Email**: jacob.parelman@asc.upenn.edu


**Office hours**: Virtual online meetings through Zoom


## Course Description, Goals and Objectives

In this hands-on course students will learn how to manage large textual datasets (e.g. Twitter, YouTube, news stories) to investigate research questions. They will work through a series of steps to collect,
organize, analyze and present textual data by using automated tools toward a final project of relevant interest.  The course will cover linguistic theory and techniques that can be applied to textual data (particularly from the fields of corpus linguistics and natural language processing).

_No prior programming experience is required._ Through this course students will gain skills writing Python programs to handle large amounts of textual data and become familiar with one of the key techniques used by data scientists, which is currently one of the most in-demand jobs.

* This course will provide an introduction to Python programming for collecting, preparing and analyzing text data from various sources including
social media (e.g. Twitter), weblogs, online news media and various publicly available archives (e.g. presidential speech archive, congressional sessions).

* Each week one session will be in lecture and seminar form and provide background for the theory and techniques and the second will be a lab session
in which students will work through programming exercises using Jupyter notebooks [A web-based programming environment well suited for data science and class-based assignments].

* By completing this course students will:
	* gain an understanding of relevant linguistic concepts for the analysis of text
	* understand the field of corpus linguistics and how its concepts and tools can be applied to text analysis questions of relevance to Communication
	* be exposed to a range of techniques from natural language processing and understand how they can be used to improve content analyses
	* gain a basic level of programming proficiency in the Python programming language and have completed a number of programming exercises to build, clean and analysis corpora of text

## Textbooks and resources

* The main readings on corpus linguistics will come from:
	* Baker, P. (2006) _Using Corpora in Discourse Analysis_. London: Continuum

* and on Python programming and NLP concepts from:
	* Bird, S., Klein, E. & Loper, E. _Natural Language Processing with Python - Analyzing Text with the Natural Language Toolkit._ Updated version for Python 3. Available free online at http://www.nltk.org/book/


## Assessment

1. **Complete the assigned readings and corpus building exercises (10%)**
	* Readings for each week will be posted on Canvas when electronic versions are available or taken from one of the recommended textbooks.
	* Throughout the course you will be asked to complete short writing exercises that will be used to build a class corpus for analysis. Details will be discussed in class and posted on Canvas.
		* Examples of the prompts might be:
			* _Describe your interest in Communication research._
			* _Look at this picture closely for a minute and then write a paragraph describing what you see._
			* _Write about your earliest memory._
			* _Create a recipe for a fried or boiled egg for your room mate who doesn't know how to cook._
2. **Attend weekly lab sessions and complete the assigned exercises (40%)**
    * Thursday class sessions will _usually_ be programming labs. Students are required to bring a laptop that can connect to the ASC network. Please contact the me if this is difficult and we can see if a machine can be made available for use in lab.
	* We will be using Jupyter notebooks to learn Python, which are a web-based interactive programming environment. Assignments will be completed in this and submitted to the instructor. Details of using this system for assignments will be covered in the first lab session.
	* Weekly assignments will be due at 5pm on the Tuesday following lab session (see schedule for details). These assignments are intended to help students practice the programming concepts and structures introduced in lab and build confidence. They should not be difficult or take excessive time but they do build from week to week so it is _very_ important to keep up.
3. **Complete a project that uses the techniques and theory covered in class to carry out a text analysis of a specific research question agreed upon with the instructor (50%)**
    * The goal of this project is to create an engaging blog post similar those produced by data journalists after [State of the Union](https://www.washingtonpost.com/news/monkey-cage/wp/2015/01/21/the-state-of-the-union-address-in-a-single-figure/?utm_term=.1a2854849261) addresses or on a topic like ['How men and women talk about love'](https://www.nytimes.com/interactive/2017/11/07/upshot/modern-love-what-we-write-when-we-write-about-love.html) in the NYTimes recently.

    * The steps in the project are:
         1. Decide upon a tractable research question that involves analysis of textual data, e.g.:
            * _Did Hillary Clinton's language as candidate change between 2008 and 2016?_
            * _What makes and when is Donald Trump happy (as evidenced on Twitter)?_
            * _What characterizes the online media's discussion of poverty/immigration/etc.?_
            * _From smoking to vaping - Examining online testimonials of e-cigarette users_
            * _Comparing portrayal of women in rap and country music__
         2. Identify, retrieve and prepare a relevant corpus, e.g.
            * Clinton 2008 and 2016 campaign speeches
            * Trumps tweets since 2014
            * Online news coverage of poverty/immigration/..
            * User stories from online vaping forum, etc.)
            * Representative samples of song lyrics
         3. Carry out linguistic analysis of corpus, e.g.
            * Construct comparative frequency lists of 2008 and 2016 speeches by Clinton, identify keywords, collocations and examined and interpret concordance listings
            * Apply appropriate sentiment analysis techniques to Trump tweet corpus, cluster tweets by sentiment and time, examine distinctive words and phrases
            * Collocation analysis of topic related words (e.g. _poverty, poor, low-income_ or _immigration, immigrants, illegals, illegal aliens_)
            * Create n-gram frequency lists and compare collocations and patterns relating to _smoking_ and _vaping_
            * Examine and compare collocates of words for women between two genres
         4. Visualize data
            * Find appropriate ways to communicate the most important and relevant results from step 3. This might be use a frequency list, concordance listings, a scatter plot of words and phrases, etc.
         5. Interpret findings
            * How does your text analysis answer your research question?
            * Why and how does it matter?
         6. Write up in a blog post
	    * Some examples of the style and length of blog post will be discussed.
            * Data science and particularly textual and language analysis focused posts on `medium.com` are good models for what you are trying to produce.   

            These steps will be scheduled throughout the course allowing for the instructor to help you find a manageable problem, acquire the necessary data and be able to carry out the appropriate computational analysis.

     * More details of the kinds of projects that would be appropriate and manageable will be discussed during the first few weeks of class.



## Note about learning programming

A central goal of this class is to help students begin to develop programming skills that they can use to approach questions of interest using the growing amounts of textual data available in the era of 'big data'. But like learning any new skill, such as a new language, it takes time and can be frustrating at first. This course does not require students to have any programming background. Realistically it is not possible to become a fully proficient programmer in just one semester. However, the lab sessions and assignments are focused on helping you begin this process and to become comfortable with reading, understanding and modifying Python code examples that you can find on the web etc.



## Course Schedule

* **N.B.** - This is a tentative schedule that is subject to change

### Week 1 - Overview
* Thur 01/21/21 - **Course overview**
	* Language as a social tool and language  data as traces of communicative acts
	* Review of course overview notebook

### Week 2 - Introduction
* Tue 01/26/21 - **Introduction to Corpus Linguistics and NLP**
	* _Topics_:
	   * What are _corpus linguistics_ and _natural language processing_?
	       - Counting _words_ and finding patterns in language
	       - Constructing _models_ of language data
	* _Coding_:
	   * Jupyter and Python basics
	       - Using JupyterHub and notebooks
	       - Markdown
	       - Python string objects

* Thur 01/28/21 - **Lab session 1**
	* _Topics_:
		* Jupyter notebooks.
		* First scripts for text analysis.
		* Working with Python `string` objects
			* `string` functions
			* Indexing and slicing `string` objects
		* Reading text files into string objects.
	* __Assignment 1__: Working with Python String Objects

### Week 3 - What is a corpus?
* Tue 02/02/21 - **Types of corpora**
    - _Topics_:
        * What is a corpus?
        * Types of corpus
          - _general vs specialized_
          - _matched genre vs variety_
          - _synchronic vs diachronic_
    - _Coding_:
        * Working with sequences using Python `list` objects
        * List indexing and slicing
    - **Readings**: _Baker Chs. 1&2_; _NLTK Book Ch. 1 (sections 1, 2 & 4 )_ http://www.nltk.org/book/ch01.html  
    - **Assignment 1 DUE 5pm** - Submit through JupyterHub

* Thur 02/04/21 - **Lab session 2**
	* _Topics_:
	    * Working with Python `list` objects
	    * Basic tokenization, turning text strings to lists of strings
	    * Listing files and directories
	* __Assignment 2__: Working with Python lists

### Week 4 - Frequency lists  
* Tue 02/09/21 - **How and what to count**
    - _Topics_:
        * Word and N-Gram lists
        * Dispersion
    - _Coding_:
        * `Counter` object
        * Loops
        * Conditions
    - __Readings__: _Baker Chs. 3_; _NLTK Book Ch. 2 (esp. sections 1,2&4 )_ http://www.nltk.org/book/ch02.html
    - **Assignment 2 DUE 5pm** - submit through JupyterHub

* Thur 02/11/21 - **Lab session 3**:
	* _Topics_:
	    * Using `Counter` to create frequency distributions.
	    * `for` loops
	    * Conditional constructions
	    * Filtering lists and objects.

### Week 5 - Finding, building and using corpora - Part 1

* Tue  02/16/21 - **Corpus compilation**
    - _Topics:_
    	* Extracting texts from documents
        * Organizing a corpus
        * Using APIs to compile a corpus (e.g. Genius, Twitter)
    - _Coding:_
        * Dictionaries
        * Writing files
        * Working with JSON
	* Functions
    - **Readings**: _Baker Chs. 3&4_; _NLTK Book Ch. 3_ http://www.nltk.org/book/ch03.html

* Thur 02/18/21 - **Lab session 4**:
    - _Topics_:
        * Splitting up a string into chunks
        * Writing a `string` object to a file
        * List of dictionaries structure
	* Functions
    - __Assignment 4__: Creating a text corpus


### Week 6 - Concordance Analysis
* Tue 02/23/21 - **Working with KWIC concordances**
    - _Topics_:
    	* Using concordances (Keyword-in-context = KWIC) to find patterns and meaning
    - _Coding_:
        * Nested lists
        * Sorting lists
	* Functions
    - **Readings**: _Baker Ch. 4_; _NLTK Book Ch. 3_ http://www.nltk.org/book/ch03.html

* Thur 02/25/21 - **Lab session 5**
    - **Assignment 4 DUE 12pm** - submit through JupyterHub
    - _Topics_:
         * sorting lists
         * the list-of-lists structure
         * creating and using functions
    - __Assignment 5__: Analysis KWIC concordances


### Week 7 - Finding, building and using corpora - Part 2
* Tue 03/02/21 - **Online corpus compilation**
    - _Topics_:
        * Using APIs to compile a corpus (e.g. Twitter)
	* Understanding web page structures
	* HTML and CSS basics
        * Using web scraping and crawling to build a corpus
    - _Coding_:
        * Using `requests` for web page and API access
	* Working with JSON in Python
	* Using `BeautifulSoup` to extract text from HTML
    - **Readings**: _Baker Chs. 2_; _NLTK Book Ch. 3_ http://www.nltk.org/book/ch03.html
    - **Assignment 5 DUE 5pm**

* Thur 03/04/21 - **Lab session 6**
    - _Topics_:
        * downloading web pages
	* navigating HTML documents and extracting text
        * code blocks in functions
    - __Assignment 6__: Building a web corpus


### Week 8 - Collocation
* Tue 03/9/19 - **Words _have_ friends**
    - _Topics_:
        * Discovering meaning through context
	* Comparing words through collocation
	* Collocation profiles
    - _Coding_:

    - **Readings**: _Baker Ch. 5_; _NLTK Book Ch. 4 (sections 1&2)_ http://www.nltk.org/book/ch03.html
    - **Assignment 6 DUE 5pm**


* Thur 03/11/19 - **NO CLASS - SPRING BREAK**


### Week 9 - Keyness
* Tue 03/16/21 - **Discovering distinctive vocabulary**
    - _Topics_:  
        * 'Aboutness' in text
        * Kinds of comparison
        * Statistical significance and association
    - _Coding_:

    * **Readings**: _Baker Ch. 6_; _NLTK Book Ch. 4 (sections 3&4)_ http://www.nltk.org/book/ch04.html

* Thur 03/18/21 - **Lab session 8**
    - _Topics_:  


### Week 10 - Introduction to NLP
* Tue 03/23/21 - **Core concepts and techniques**
    * NLP pipeline
  	* Key tasks: POS tagging, parsing, anaphora resolution, role identification
  	* Example Applications
    * **Readings**: _NLTK Book Ch. 1 (section 5)_ (http://www.nltk.org/book/ch01.html) and _Ch. 5_ (http://www.nltk.org/book/ch05.html)
    * **Assignment 6 DUE 5pm**
* Thur 03/25/21 - **Lab session 7**: Using NLTK; NLP Pipeline

### Week 11 - NLP: Affect and Sentiment analysis #1
* Tue 03/30/21 - ** NO CLASS - Engagement Day **

* Thur 04/01/21 - **Measuring emotion in text**
    * **Lab session 8**: Using affect lexicons
  	* **Assignment 7 DUE 5pm**

### Week 12 - NLP: Affect and Sentiment analysis #2
* Tue 04/06/21 - **Sentiment classification**
  	* Supervised machine learning
  	* Building a training corpus
  	* Measuring accuracy
    * **Readings**: _NLTK Book Ch. 6_ (http://www.nltk.org/book/ch06.html)
  	* **Assignment 8 DUE 5pm**

* Thur 04/08/21 - **Lab session 9**: Building a sentiment classifier

### Week 13 - NLP: Named Entity Recognition (NER): Who, what, when and where?
* Tue 04/13/21 - **Identifying actors and actions in text**
  	* **Readings**: _NLTK Book Ch. 7_ (http://www.nltk.org/book/ch07.html)
  	* **Assignment 9 DUE 5pm**
* Thur 04/15/21 - **Lab session 10**: NER and parsed corpora

### Week 14 - NLP: Topic models
* Tue 04/20/21 - **Discovering clusters of words in text collections**
	* **Assignment 10 DUE 5pm**
* Thur 04/22/21 - **Lab session 11**: Topic models and visualization

### Week 15 - Class projects
* Tue 04/27/19 - **Project presentations**
* Thur 04/29/19 - **Project presentations**
