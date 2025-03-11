# JUPYTER NOTEBOOK

![Jupyter logo](https://github.com/leone-nyaga/Data_Analysis/blob/main/images/jupyter.png)

Jupyter Notebook is an incredibly powerful tool for interactively developing and presenting data science projects. It combines code, visualizations, narrative text, and other rich media into a single document, creating a cohesive and expressive workflow.

## What is Jupyter Notebook?

At its core, a notebook is a document that blends code and its output seamlessly. It allows you to run code, display the results, and add explanations, formulas, and charts all in one place. This makes your work more transparent, understandable, and reproducible.

Jupyter Notebooks have become an essential part of the data science workflow in companies and organizations worldwide. They enable data scientists to explore data, test hypotheses, and share insights efficiently.

As an [open-source project](https://jupyter.org), Jupyter Notebooks are completely free. You can download the software directly from the [Project Jupyter website](https://jupyter.org/install) or as part of the [Anaconda data science toolkit](https://jupyter.org/install).

Jupyter Notebooks support multiple programming languages like R, Julia, and Scala are also supported. But it's commonly used with Python.

## Installation

You can install using Anaconda or pip3.

```bash
pip3 install jupyter
```

To run:

```bash
jupyter notebook
```

Then copy the url provided and paste in on a browser

## What is an ipynb File?

The short answer: each .ipynb file is one notebook, so each time you create a new notebook, a new .ipynb file will be created.

The longer answer: Each .ipynb file is a text file that describes the contents of your notebook in a format called JSON. Each cell and its contents, including image attachments that have been converted into strings of text, is listed therein along with some metadata.

You can edit this yourself — if you know what you are doing! — by selecting "Edit > Edit Notebook Metadata" from the menu bar in the notebook. You can also view the contents of your notebook files by selecting “Edit” from the controls on the dashboard

However, the key word there is can. In most cases, there's no reason you should ever need to edit your notebook metadata manually.

## The Notebook Interface

Now that you have an open notebook in front of you, its interface will hopefully not look entirely alien. After all, Jupyter is essentially just an advanced word processor.

Why not take a look around? Check out the menus to get a feel for it, especially take a few moments to scroll down the list of commands in the command palette, which is the small button with the keyboard icon **(or Ctrl + Shift + P)**.

![jupyter interface](https://github.com/leone-nyaga/Data_Analysis/blob/main/images/jupyter%20notebook%20interface.png)

## ZEN OF PYTHON

![zen of python](https://github.com/leone-nyaga/Data_Analysis/blob/main/images/zen%20of%20python.png)

There are two key terms that you should notice in the menu bar, which are probably new to you: **Cell** and **Kernel**. These are key terms for understanding how Jupyter works, and what makes it more than just a word processor. Here's a basic definition of each:

+ The kernel in a Jupyter Notebook is like the brain of the notebook. It’s the "computational engine" that runs your code. When you write code in a notebook and ask it to run, the kernel is what takes that code, processes it, and gives you the results. Each notebook is connected to a specific kernel that knows how to run code in a particular programming language, like Python.

+ A cell in a Jupyter Notebook is like a block or a section where you write your code or text (notes). You can write a piece of code or some explanatory text in a cell, and when you run it, the code will be executed, or the text will be rendered (displayed). Cells help you organize your work in a notebook, making it easier to test small chunks of code and explain what’s happening as you go along.

## CELLS

We’ll return to kernels a little later, but first let’s come to grips with cells. Cells form the body of a notebook. In the screenshot of a new notebook in the section above, that box with the green outline is an empty cell. There are two main cell types that we will cover:

+ A **code cell** contains code to be executed in the kernel. When the code is run, the notebook displays the output below the code cell that generated it.
+ A Markdown cell contains text formatted using [Markdown](https://www.markdownguide.org/basic-syntax/) and displays its output in-place when the Markdown cell is run.

The first cell in a new notebook defaults to a code cell. Let’s test it out with a classic "Hello World!" example.

Type **print('Hello World!')** into that first cell and click the **Run** button in the toolbar above or press **Ctrl + Enter** on your keyboard.

The result should look like this:

![Hello world](https://github.com/leone-nyaga/Data_Analysis/blob/main/images/notebook_hello_world.png)

