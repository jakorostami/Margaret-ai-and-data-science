# Margaret-ai-and-data-science
AI and Data Science for Margaret Educational Community and School <br>
 زیرەکی دەستکرد و زانستی داتا بۆ کۆمەڵگە و قوتابخانەی پەروەردەیی مارگرێت <br>
Zekaya sûnî û Zanista Daneyan ji bo Civaka Perwerdehiyê û Dibistana Margaret


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
   - 


4. Data Cleaning
   - Common data problems / کێشەی بەردەوامی داتا / Pirsgirêka berdewamiya data
   - Handling missing values / مامەڵەکردن لەگەڵ ئەو زانیاریانەی کە نەماوە / Birêvebirina datayên winda
   - Data types and conversion / جۆرەکانی داتا و گۆڕینی / Cureyên datayên û veguherîn
   - Creating clean datasets / دروستکردنی داتا سێتی پاک / Çêkirina setên datayên paqij
   - Pandas basics for data manipulation / بنەماکانی پانداس بۆ دەستکاریکردنی داتا / Bingehên Pandas ji bo manipulasyona datayên
   - 

