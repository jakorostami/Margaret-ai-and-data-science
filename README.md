# Margaret-ai-and-data-science
AI and Data Science for Margaret Educational Community and School <br>
 زیرەکی دەستکرد و زانستی داتا بۆ کۆمەڵگە و قوتابخانەی پەروەردەیی مارگرێت <br>
Zîrekîya destkirî û Zanista Data ji bo Civaka Perwerdehiyê û Dibistana Margaret

![image](https://github.com/jakorostami/Margaret-ai-and-data-science/blob/main/assets/main.jpg?raw=true)

## Introduction / پێشەکی / Pêşekî

Welcome to the repository for AI & Data Science that has been created for Margaret. We will be focusing on learning by doing, which means we will implement theory into practice with Python code. <br>

بەخێربێن بۆ کۆگای AI & Data Science کە بۆ مارگرێت دروست کراوە. ئێمە سەرنجمان لەسەر فێربوون بە ئەنجامدان دەبێت، واتە بە کۆدی پایتۆن تیۆری جێبەجێ دەکەین بۆ پراکتیک <br>

Bi xêr hatin bo depoya AI û Data Science ku ji bo Margaret hatiye afirandin. Em ê balê bikişînin ser fêrbûna bi kirinê, ku tê vê wateyê ku em ê teoriyê bi koda Pythonê bixin praktîkê.


## Starting point - Install Python / دەستپێکردن - دامەزراندنی پایتۆن / Destpêkirin - Pythonê saz bike

Before we do anything, we need to download and install some apps so you can start. <br>

پێش ئەوەی هەر کارێک بکەین پێویستە هەندێک ئەپ دابەزێنین و دایبمەزرێنین بۆ ئەوەی بتوانیت دەست پێبکەیت. <br>

Berî ku em tiştekî bikin, dibê em hin sepanan dakêşin û saz bikin da ku hûn bikaribin dest pê bikin.

**Download Python (macOS and Linux/Ubuntu requires you to open the Terminal)**
   - Windows: https://www.python.org/downloads/release/python-31210/
   - macOS via brew: `brew install python@3.12`
   - macOS via pyenv: `curl https://pyenv.run | bash`
   - Linux/Ubuntu: `sudo apt install python3.12 python3.12-venv python3.12-dev -y`


## Create a virtual environment / ژینگەیەکی مەجازی دروست بکە / Jîngehek mecazî biafirîne

What is a virtual environment? A virtual environment is for you to be working on your projects with certain settings on your computer without configuring for the whole environment in the computer, only a made-up environment on the computer. This makes it easy for you to create multiple projects with different settings if you need it. For instance, building AI with certain settings and doing data analysis with different settings. <br>

ژینگەی مەجازی چییە؟ ژینگەی مەجازی ئەوەیە کە تۆ بە هەندێک ڕێکخستن لە کۆمپیوتەرەکەتدا کار لەسەر پڕۆژەکانت بکەیت بەبێ ئەوەی ڕێکبخەیت بۆ تەواوی ژینگەی ناو کۆمپیوتەرەکە، تەنها ژینگەیەکی دروستکراو لەسەر کۆمپیوتەرەکە. ئەمەش ئاسانکاریت بۆ دەکات کە چەندین پڕۆژە بە ڕێکخستنی جیاواز دروست بکەیت ئەگەر پێویستت پێی بێت. بۆ نموونە دروستکردنی AI بە هەندێک ڕێکخستن یان ئەنجامدانی شیکاری ئاماری بە ڕێکخستنە جیاوازەکان. <br>

Jîngeheke mecazî çi ye? Jîngeheke mecazî ji bo we ye ku hûn li ser projeyên xwe bi mîhengên diyarkirî li ser komputerê bixebitin bêyî ku hûn tevahiya jîngehê di komputerê de mîheng bikin, tenê jîngeheke çêkirî li ser komputerê ye. Ev yek ji we re hêsan dike ku hûn gelek projeyan bi mîhengên cûda biafirînin ger hewce bike. Mînakî, avakirina AI bi mîhengên diyarkirî an kirina azmayîş amarî bi mîhengên cûda. <br>


1. **Windows**
  - For Windows you will also want to install Anaconda: https://www.anaconda.com/download
  - Open cmd (command prompt)
  - Create a project folder: `mkdir my-project`
  - Go to the project folder: `cd my-project`
  - Create a new environment: `conda create --name myenv python=3.12`
  - To activate the environment: `conda activate myenv`
  - Now you can install Python packages either with `pip install` or `conda install`

2. **macOS/Linux**
  - Open the terminal
  - Create a project folder: `mkdir my-project`
  - Go to the project folder: `cd my-project`
  - Create a new environment: `python3.12 -m venv myenv`
  - To activate the environment: `source myenv/bin/activate`
  - Now you can install Python packages with `pip install`


## Program structure in this course / پێکهاتەی بەرنامە لەم خولەدا / Avahiya bernameyê di vê dersê de

### Data Science
1. Introduction / پێشەکی / Pêşekî
   - What is Data Science? / زانستی داتا چییە؟ / Zanista Data çi ye?
   - Real world applications kids can relate to / بە کارهێنانی ڕاستەقینە منداڵان دەتوانن پەیوەندییان پێوە بکەن / Bikaranîn rastîn ên ku zarok dikarin pê re têkilî daynin
   - Basic Python for data (variables, lists, dictionaries) / پایتۆنی بنەڕەتی بۆ داتا (ڤارییابەل، لیست، دیکشەنەری) / Python bingehîn ji bo daneyan (vârîâbel, lîste, dîkşenerî)

2. Data Collection / کۆکردنەوەی زانیاری / Berhevkirina zanyarî
   - Data sources (web, sensors, surveys) / سەرچاوەی زانیاری (وێب، سەنسۆر، ڕاپرسی) / Çavkaniyên daneyan (web, sensor, rapirsî)
   - Simple web scraping with BeautifulSoup (for older kids) / وێب سکرێپینگ سادە بۆ منداڵانی گەورەتر / Web scrapinga hêsan ji bo zarokên mezin
   - CSV, JSON file formats / فۆرماتەکانی پەڕگەی CSV، JSON / Formatên pelan ên CSV, JSON
   - APIs for kids (weather API, NASA API) / API بۆ منداڵان (API کەش و هەوا، NASA API) / API-yên ji bo zarokan (API-ya hewayê, API-ya NASA-yê)
   - Data privacy and ethics / پاراستنی نهێنی و ئەخلاقی داتا / Nepenîtiya data û exlaq

3. Data Cleaning / تەمیزکردنی داتا / Temîzkirina data
   - Common data problems / کێشەی بەردەوامی داتا / Pirsgirêka berdewamiya data
   - Handling missing values / مامەڵەکردن لەگەڵ ئەو زانیاریانەی کە نەماوە / Birêvebirina datayên winda
   - Data types and conversion / جۆرەکانی داتا و گۆڕینی / Cureyên datayên û veguherîn
   - Creating clean datasets / دروستکردنی داتا سێتی تەمیز / Çêkirina setên datayên temîz
   - Pandas basics for data manipulation / بنەماکانی پانداس بۆ دەستکاریکردنی داتا / Bingehên Pandas ji bo manipulasyona datayên
  
4. Visualization / نیشاندان / Nîşandanê
   - Importance of data visualization / گرنگی بینینی داتا / Girîngiya dîtbarîkirina daneyan
   - Basic charts with Matplotlib /  هێڵکارییە سادە لەگەڵ ماتپڵۆتلیب / Hêlkarîyên bingehîn bi Matplotlib re
   - Interactive visualizations with Plotly / بینینی کارلێککارانە لەگەڵ پلۆتلی / Dîtbarîkirinên karlêkirin bi Plotly re
   - Creating dashboards with Streamlit / دروستکردنی داشبۆرد بە ستریملیت / Çêkirina dashboardan bi Streamlit re
   - Visual storytelling with data / چیرۆکگێڕانی بینراو بە داتا / Çîrokbêjiya dîtbarî bi data

5. Descriptive Statistics / پێناسینی ئاماری / Pênasînî amarî
   - Mean, median, mode
   - Range, variance, standard deviation
   - Percentiles and quantiles
   - Correlation
   - Practical examples with data

6. Exploratory Analysis / کەشفکردنی ازمایەش / Keşfkirina azmayîş
   - Asking questions of data / پرسیارکردن لە داتا / Pirsînkirina ji data
   - Hypothesis formation / دروستبوونی گریمانە / Damezrandina girîmanî
   - Testing relationships / تاقیکردنەوەی پەیوەندییەکان / Ceribandina têkiliyan
   - Finding patterns and outliers / دۆزینەوەی نەخش و اوتلایەر / Dîtina nexş û outlier
   - Creating insights from data / دروستکردنی تێگەیشتن لە داتا / Afirandina têgihiştinê ji data
  
7. Machine Learning Basics
   - What is machine learning?
   - Supervised vs unsupervised learning
   - Classification
   - Regression
   - Evaluating models

8. Data Science Projects
   - Weather analysis
   - Sports statistics
   - Social media trends
   - Environmental data
   - Personal data collection projects


### AI

1. Introduction
   - What is Artificial Intelligence?
   - History of AI
   - Types of AI
   - Ethical considerations
   - Setting up tools and environment
  
2. Fundamentals
   - Problem solving with algorithms
   - Search algorithms
   - Game playing AI
   - Rule based systems
   - Introduction to neural networks

3. Machine Learning for AI
   - Supervised learning for classification
   - Computer Vision basics
   - Training vs testing data
   - Model evaluation
   - Transfer learning concepts

4. Computer Vision
   - Image recognition basics
   - Object detection
   - Face detection
   - Image generation
   - Projects with computer vision
  
5. Natural Language Processing
   - Text analysis basics
   - Sentiment analysis
   - Chatbots
   - Working with LLMs
   - Text generation
  
6. Speech Technologies
   - Speech-to-text
   - Text-to-speech
   - Voice assistants
   - Building simple voice commands
   - Sound classification
  
7. Generative AI (GenAI)
   - Introduction to generative models
   - Introduction to Transformers
   - Text generation
   - Image generation
   - Creative AI projects
  

8. AI Projects
   - Simple chatbot
   - Object detector
   - Voice controlled applications
   - Image classification
   - Generative AI
  

## Age groups for teacher guidance

### Ages 9-10
- Visual programming
- Simplified explanations with animations
- Guided activities
- Focus on ethics and imagination
- Heavily pre-made projects

### Ages 11-12
- Mix of block and text based programming
- More hands-on activities
- Introduction to Python with clear examples
- Guided exploration with checkpoints
- Team based projects

### Ages 13-14
- Full Python programming
- More complex datasets
- Introduction to real-world applications
- Independent exploration
- Individual and group projects

### Ages 15-16
- Advanced Python concepts
- Industry relevant tools and libraries
- Research inspired projects
- Career connections (Asiacell, oil companies, and banks etc)
- Potential internship/mentorship connection with companies and universities
   
