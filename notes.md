## todo

- hello airPassengers
  - first draft with polars and seaborn ok! [x]
  - redo with native polars plot (uv add altair)
- what about prophet?
## quarto

- how to make it use uv?
    - as of now the main way is to activate venv, see https://github.com/quarto-dev/quarto-cli/discussions/11257
- in slides default is not to show code
- it does take a moment to activate a render environment

## Agenda
## Refs
- books on time series forecasting

## time is 25'!!!

## Proposal

submitted https://pretalx.com/pycon-lithuania-2025/talk/review/YTLCMVHJ3HGGYFQCDVLP8CL39DBVQF7E

**Title**: A Crash course in Time Series Forecasting from Naive to Foundational

### abstract
Forecasting is a common activity that has clear business value in various domains but it is not a very common skill that Data Scientists have or feel confident about. In this crash course I will cover the fundamentals of Time Series forecasting from the basic methods to more advanced techniques. I will do this showcasing practical code examples using libraries from Nixtla.
### description
This is a technical talk that aims to provide the essential elements for a Data Scientist to go from zero knowledge of time series forecasting to being able to code a forecasting system that can evolve from a basic setup that can be put in production.

After a brief introduction to motivation why we forecast and the different domains and use cases, the rest of the presentation will consists of code examples that will exemplify the various steps of a data science lifecycle. We will start from looking at the data, implementing a baseline model and set up an evaluation framework. From there we will explore different type models from statistical to ML and different techniques (probabilistic forecasting and hierarchical forecasting). Finally we will comment on more advanced time series methods like neural methods and foundational models for time series.

The code examples will make use of Nixtla libraries, because we think they currently represent the state of the art for time series forecasting with Python both in term of range of functionality and consistency of API. Most of the concepts and techniques can translate to other frameworks.




Agenda:
- why we forecast
- why nixtla
- domain
	- 3 use cases
		- demand in supply chain (business)
		- expenses on a card? (customers)
		- energy?
- data
- explore (and take candidates in behaviour)
- start with a baseline
- evaluate
- stats forecast
- ml forecast
- decomposition
- probabilistic (conformal or not)
- hierarchical
- neural
- foundational
- refs


## previous abstract

**Time Series Forecasting and Nixtla Ecosystem**  
Predicting the future, or - as Data Scientist like to call it - Time Series Forecasting, is a time-honored activity where people get paid to be wrong.  
We will first review some of the basic concepts and methods for creating and evaluating predictions, then we will explore Nixtla's open source ecosystem: a recently released set of libraries providing the state-of-the-art implementations for most classical and modern forecasting technologies (statistical, hierarchical, machine learning, neural) that has the potential to become the reference framework in the field.