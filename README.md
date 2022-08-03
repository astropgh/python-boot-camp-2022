**2020**: [GitHub](https://github.com/astropgh/astropgh-boot-camp-2020) / [website](https://astropgh.github.io/astropgh-boot-camp-2020/)

**2021**: [GitHub](https://github.com/astropgh/python-boot-camp-2021) / [website](https://astropgh.github.io/python-boot-camp-2021/)

**2022**: [GitHub](https://github.com/astropgh/python-boot-camp-2022) / [website](https://astropgh.github.io/python-boot-camp-2022/)

Welcome to the 2022 AstroPGH Python Boot Camp and Weekly Seminar Series for summer undergraduate students and early PhD students new to Python.  This program is designed to help you learn the basics of using Python for astrophysics research.

We will start with a 3 day Python coding boot camp to help get everyone off the ground with their research.

Then we will have a weekly seminar series to discuss more advanced topics, including communication skills (reading, plotting, storytelling, and writing), code optimization, and statistics/machine learning. Our hope is to create a sense of community in spite of the remote operations this year, so that you can help others, can seek help, and can interact with each other.

## Boot Camp
### Installation and Setup
#### Python
Please install Python 3 before the Boot Camp. I recommend using the [Anaconda](https://www.anaconda.com/products/individual) package manager **_for Python 3.9_** and then install the following packages in the terminal:
```bash
conda install numpy scipy astropy matplotlib jupyter ipython
conda install -c astropy astroquery
conda install -c conda-forge jupyterlab
```

- [Conda Users Guide](https://conda.io/docs/user-guide/index.html)
- [Astropy Install Instructions](http://docs.astropy.org/en/stable/install.html)

#### Test Your Installation

1. Open a new terminal.
2. Type `ipython` into the terminal to open an interactive python session (the prompt should say `In [1]:`).
3. Copy this code:
```python
import numpy
import scipy
import astropy
import matplotlib
import astroquery
```
4. Type into the iPython shell the word `paste`, and press enter.
5. If no errors are raised, you're ready for bootcamp. You may close the terminal window.

If you are having difficulties with installation, please do not hesitate to reach out to Brett Andrews on Slack or via email.

### Instructors
- [Brett Andrews](https://bretthandrews.github.io/): Python Basics
- [Alan Pearl](https://alanpearl.github.io/): Data Structures & Functions and Modules
- [Yasha Kaushal](https://yashakaushal.github.io/): Matplotlib I
- [Emily Biermann](https://embiermann.github.io/): Numpy I
- [Zach Lewis](https://zachjlewis.github.io/): Numpy II
- [Travis Court](https://courtt.github.io/): Numpy III and IV
- [Biprateep Dey](https://biprateep.de/): Astropy I
- [David Setton](https://davidjsetton.github.io/): Astropy II
- Collin McLeod: Matplotlib II
- Lina Florez: Pandas


### Schedule

| Time (EDT) | Monday (5/23) | Tuesday (5/24) | Wednesday (5/25) |
|:-----:|:-----:|:-----:|:-----:|
| 10:00-11:15 | Python Basics | Numpy I | Astropy I |
| 11:45-1:00 | Data Structures | Numpy II | Astropy II |
| 2:00-3:15 | Functions and Modules | Numpy III | Matplotlib II |
| 3:45-5:00 | Matplotlib I | Numpy IV | Pandas |


## Seminar Series

Wednesdays from 2-3 pm EDT

| Date | Title | Speaker |
|:-----:|:-----:|:-----:|
| 6/1  | Code Review | Ashod Khederlarian|
| 6/8  | Code Review | [Travis Court](https://courtt.github.io/)|
| 6/15 | [Best Practices for Intermediate Level Python Development](seminars/python_best_practices_2022-06-15.pdf) | [Daniel Perrefort](http://djperrefort.com/) |
| 6/22 |  |  |
| 6/29 | [AstroCoffee Tips](seminars/astrocoffee_tips_2022-06-29.pdf) | [Brett Andrews](https://bretthandrews.github.io) |
| 7/6  | Show and Tell: Tips, Tricks, Hacks, and Tools |  |
| 7/13 | [Python Packaging Basics](seminars/Python_Packaging_Basics_Alan_Pearl_2022-07-13.pdf) |  [Alan Pearl](https://alanpearl.github.io/) |
| 7/20 | [How to Train Your Perceptron](https://github.com/biprateep/Tutorials/blob/master/how-to-train-your-perceptron-1.ipynb) | [Biprateep Dey](https://biprateep.de/) |
| 7/27 | [Guide to LaTeX](seminars/latex_2022-07-27.pdf) [(tex source file)](seminars/latex_2022-07-27.tex) | Marcell Howard |
| 8/3  | [Jumpstart Your Paper](seminars/jumpstart_your_paper_2022-08-03.pdf) | [Brett Andrews](https://bretthandrews.github.io/) and [Rachel Bezanson](https://rachelbezanson.github.io/) |
| 8/10  |  |  |
| 8/17  |  |  |
| 8/24  | Intro to Git I | [Bob Caddy](http://robertcaddy.com/) |
| 8/31  | Intro to Git II | [Bob Caddy](http://robertcaddy.com/) |

<a href="url"><img style="padding: 0px 20px;" src="https://github.com/astropgh/python-boot-camp-2021/blob/main/etc/NSF_4-Color_bitmap_Logo.png?raw=true" align="left" height="128" width="128"></a>

This material is based upon work supported by the National Science Foundation grant number AST-2009251. Any opinions, findings, and conclusions or recommendations expressed on this website are those of the participants and do not necessarily reflect the views of the National Science Foundation or the participating institutions.
