# Presentation ToC

## Context, Motivation, and Goals

### Context

- Prolog as the reference LP technology

- Plenty of frameworks supporting ML in the mainstream

- Poor interoperability among ML

### Motivation 

- Need to fill the gap

- Make it possible to train ML predictors from LP

- Make it possible to use ML predictors as logic predicates

### Goals

- Design a logic API for ML
    * covering all phases of ML workflow
    * consisting of a set of logic predicates

- Design an architecture for re-using current ML and LP libraries

- Select technologies for prototyping

## Background

- General supervised learning workflow

- 2P-Kt and generators

## Contribution

### Expected Benefits

- Hybrid reasoning

- Declarative ML

- Symbolic data sources

- Model selection via resolution

### Architectural overview

- Architectural view
    * need for a library of predicates
    * and some underlying ML library
    * and for some mechanism to bind OOP and logic terms

### Main logic API

- 4 main kinds of entities: Schema, Dataset, Transformation, and Predictor
- and many low level entities such as Classification Strategy, SourceType, Parameter, Neural Network, and Layer

### Technology Selection

- DL4J on the JVM
- ScikitLearn on Python
- mention to 2ppy

## Conclusions and Future Works

- Recap

### Future Works

- Design and implement Python binding
- Support unsupervised learning as well
- Experiment with in-production hybrid systems
