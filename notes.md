## new plan

- just adjust previous presentation
- no code execution (once in notebook and take screenshots!)

todo new plan:
- list all slides in todo [x]
- start with the easiests!
- test adding image [x]
- test adding code (without execution) [x]

slides (target is 20)
1. agenda
2. me [x]
3. why [x]
4. time [x]
5. nixtla [x]
  - add words?
6. methodology [x]
7. airpassengers
8. baseline (options) [x]
9. baseline (code)
10. measure (metrics)
11. cross validation [x]
12. measure (code)
13. statsforecast
14. M5 [x]
15. mlforecast [x]
16. probabilistic forecast
17. hierarchical [x]
18. neural forecast
19. foundational [x]
20. refs
completed: 11/20

(skip decomposition?)

## todo

plan:
- finish snippets of code
- write snippets of code in slides
- test how not to execute code in slides
- finish writing the text


- intro 4/5-7
  - 1. agenda [x]
    - first draft [x]
    - fix at the end
  - 2. me slide [x]
  - 3. why (business) [x]
    - first draft [x]
    - domain?
  - 4. time
    - first draft [x]
  - scope/focus?
  - data (about numerosity and layout)
  - why nixtla
- basics
  - 1. hello airPassengers [x]
    - first draft with polars and seaborn ok! [x]
    - redo with plotly [x]
    - what could be a good url ref for airpassengers?
    - stats forecast has the good url! https://nixtlaverse.nixtla.io/statsforecast/docs/getting-started/getting_started_short.html
  - 2. hello evaluate
  - 3. naive baseline
  - 4. more time series: M5
- what about prophet?

## nixtla

- statsforecast build fails on my mac from 1.7.7 (because of moving from numba to C++)
    - using 1.7.6 (released july 2024)
    - 1.7.7 released sep 2024
    - 2.0.0 released nov 2024

## quarto

- how to make it use uv?
    - as of now the main way is to activate venv, see https://github.com/quarto-dev/quarto-cli/discussions/11257
- in slides default is not to show code
- it does take a moment to activate a render environment
- argh altair with quarto reveal has issues! https://github.com/quarto-dev/quarto-cli/issues/10903 (works in chrome, not in preview)

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