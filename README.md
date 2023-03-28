# Kaggle Competition: Making STEM Materials Accessible

## Introduction
Millions of students with learning, physical, or visual disabilities are unable to read conventional print. Unfortunately, most educational materials for science, technology, engineering, and math (STEM) fields are inaccessible to these students. While technology exists to make written content accessible, it remains challenging and resource-intensive to make educational visuals such as graphs accessible. This leads to a limited availability of educational materials for students with learning differences, unless machine learning can help bridge this gap.

The goal of this Kaggle competition is to extract data represented by four types of charts commonly found in STEM textbooks. Participants are expected to develop an automatic solution trained on a graph dataset to make reading graphs accessible to millions of students with a learning difference or disability.

## Objective
The objective of this competition is to predict the data series represented by four kinds of scientific figures (or charts): bar graphs, dot plots, line graphs, and scatter plots. The predicted data series are evaluated by a combination of two metrics, Levenshtein distance for categorical data types and RMSE for numerical data types. The overall score is the mean of the similarity scores over all instances.

## Evaluation Metric
The predicted data series are evaluated by a combination of two metrics, Levenshtein distance for categorical data types and RMSE for numerical data types. The overall score is the mean of the similarity scores over all instances. For a detailed explanation of the evaluation metric, see the competition's evaluation page.

## Submission
Submissions will be made through Notebooks. The submission file will contain predicted series for one axis of a figure in the test set, where, for instance, abc123_x would give predictions for axis x in figure abc123. The values of the series will be within a single string and delimited by ;. The submission file will of cource be named submission.csv and contain a header. Each row in the submission file will contain predicted series for one axis of a figure in the test set, with the appropriate type for the chart the axis belongs to.

## About the Host
The competition host, Benetech, is a nonprofit organization dedicated to reducing social and economic inequity through software for social good. Benetech's initiatives are transforming how students, job seekers, and older adults across the globe read, learn, and work. The organization believes that access to information is a human right, and no person should encounter barriers to education, literacy, or employment due to differences or disabilities. The best submissions will be adopted into Benetech's PageAI product, which converts books and other educational materials into accessible formats.

## Solution
This repository contains my solution to the Kaggle competition, including code, notebooks, and submission files. My solution will be implemented in Python and utilized machine learning techniques to predict the data series represented by the four types of charts. I am certain that I will achieve a top score in the competition, and my solution will be adopted into Benetech's PageAI product to make reading graphs accessible to millions of students with learning differences or disabilities.

## Conclusion
This Kaggle competition will provide an opportunity to make a significant impact on the lives of millions of students with learning differences or disabilities. By participating in the competition, I will be able to develop a solution that has the potential to transform how students access STEM materials.
