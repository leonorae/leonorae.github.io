# Midterm Project Update - Causal Discovery API
## Original Project 
My original project idea was the creation of a causal inference pipeline and API using Python packages. My motivations are increased theoretical knowledge, experience researching and comparing implementations of algorithms for use in a software project, development experience, and to spur my thought into future research ideas. 

## Goals and Accomplishments
My original goals were not very specific as the nature of my project is inherently exploratory. However, additional knowledge has allowed me to refine them. The main focus of the project has remained the same, but I have decided to focus primarily on causal discovery. The initial goals of my proposal are similar, but I have refined them and tied them to more specific deliverables.

#### Domain Knowledge and Ecosystem Research
My first and main goal with this project was to gain a better understanding of the theory of causal reasoning as well as a working knowledge of the existing model/algorithm implementations. Naturally, understanding the data that can be utilized by these models and gaining idea of the available datasets is a related subgoal.

As a deliverable, my findings should be compiled into a complete report as part of my results narrative. It should contain:
- A general overview of each package and its general purpose 
- a section organized by causal task which compares and contrast packages' implementations of applicable models and algorithms. There should be code examples for each. 
- A section documenting available datasets and which causal tasks and/or models they are suitable for (as well as some general explaination as to why certain data is suitable for certain kinds of inference) should also be present.

#### API Design and Implementation
My second goal is practical software development through the creation of a functional API with FastAPI. For initial development, I will use a single dataset. I am currently working with Sachs 2005, since it has an accessible ground-truth graph. https://www.science.org/doi/10.1126/science.1105809

The API should include at least the following. For deliverables, each of these subgoals should be accompanied by:
- Code
- Tests (Pytest)
- Documentation

##### Causal Discovery
Include at least one of each of the following, including and allowing for selection of multiple implementations if possible:

- Constraint-based methods
- Score-based methods
- Constrained functional causal models
- Hidden causal representation learning

##### Evaluation/Scoring
Include at least the following scoring functions for evaluating causal discovery:
 - BIC score
 - BDeu score
 - Generalized score with cross validation
 - Generalized score with marginal likelihood
    
##### Visualization
Include methods for delivering rendered causal network graphs and supporting plots of correlation.

#### Generalization and Expansion of API
Once the API is created and verified with tests on the initial dataset, I will begin to expand the API to handle additional data and gain experience creating functional infrastructure for ML projects.

- Add Pydantic verification (integrated with FastAPI)
- Extend API to allow use of other (small) datasets

I will keep this goal simple and restrict to a very particular data format and small data size, because implementation of a full database/object storage system to keep the scope of the project attainable.

### Accomplishments
I have made the most progress so far in the first goal. I have a much better overview-level understanding of the field and what is possible. My working documents compending learning resources, libraries, and datasets are helping me keep track of my learning progress and will serve as the base for my final knowledge report. I feel that I have the necessary knowledge to complete a good overview of the subject. With my code, I have a functional framework present and a good working idea of how I will complete the remaining goals. The experience and stumbling blocks with this project so far that I have reflected on in my updates have given me a lot of ideas about how to improve my organization and structuring of projects in the future.

## Future
### Plan for remaining weeks

Oct 19: begin implementing discovery methods

Oct 26: finish implementing discovery methods, add evaluation/scoring

Nov 2: add visualization methods to API

Nov 9: add additional functionality and flexibility to API (more options for data returned, etc.) and improve test coverage

Nov 16: implement basic generalization of API to other datasets

Nov 23: polish API, tests, docs, including prerequisites and steps to reproduce installation of project

Dec 30: Complete knowledge overview document and Final Report
