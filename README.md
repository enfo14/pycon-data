# 2018 PyCon UK - Understanding sample bias in specialised surveys

**A fundamental problem of applying surveys about specialised topics or designed for a particular community is the underlying sample bias. We have designed a simple survey that asks respondents to score a set of web services in several aspects, including the quality of their software, their social and environmental impact, and their efforts in user experience (UX) and customer support. The survey has been applied separately to the developer team at Omni Digital, and to the attendees at *2018 PyCon UK*, which took place between 15/09 and 19/09.**

The following analysis cleans up the data and uses a two-sample Kolmogorov-Smirnov test to assess whether there are any differences between the distributions of scores throughout the entire dataset, for each attribute. This is a first step towards a method to effectively recognise and assess fundamental differences in concept between two communities, as well as to explore the possibility that specialised knowledge may have a direct influence in the wider scope of things.

## Setting up the environment
To set up the development environment, use the `requirements.txt` file present in the repository to install the appropriate packages:

```
pip install -r requirements.txt
```

## Running the `jupyter` environment
To run the environment where the notebook lives, run:

```
jupyter notebook
```

A local server will be initialised on port `localhost:8888` unless otherwise specified. Open the notebook from the browser and navigate your filesystem to find the notebook of interest.

## Execute the notebook
In the notebook, a full clean run can be executed from the `Run` tab in the menu. Otherwise, any one cell may be executed by clicking the play button next to the cell, which will trigger the execution of any of the cells above the selected one as well.
