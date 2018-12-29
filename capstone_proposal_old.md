# Machine Learning Engineer Nanodegree
## Capstone Proposal
Seoul 
November 18st, 2018

## Proposal

Quick, Draw! Doodle Recognition Challenge (Kaggle Competition)

### Domain Background
Quick, Draw! is an online game developed by Google. 

"Quick, Draw!" was released as an experimental game to educate the public in a playful way about how AI works. The game prompts users to draw an image depicting a certain category, such as ”banana,” “table,” etc. The game generated more than 1B drawings, of which a subset was publicly released as the basis for this competition’s training set. That subset contains 50M drawings encompassing 340 label categories.

### Problem Statement

Since the training data comes from the game itself, drawings can be incomplete or may not match the label. You’ll need to build a recognizer that can effectively learn from this noisy data and perform well on a manually-labeled test set from a different distribution.

### Datasets and Inputs
The Quick Draw Dataset is a collection of millions of drawings across 300+ categories, contributed by players of Quick, Draw! The drawings were captured as timestamped vectors, tagged with metadata including what the player was asked to draw and in which country the player was located.

Two versions of the data are given. The raw data is the exact input recorded from the user drawing, while the simplified version removes unnecessary points from the vector information. (For example, a straight line may have been recorded with 8 points, but since you only need 2 points to uniquely identify a line, 6 points can be dropped.) The simplified files are much smaller and provide effectively the same information. I will use the simplified files because the raw file is huge.

1. test_raw.csv - the test data in the raw vector format
  Column: key_idUnique Identifier
          countrycode2-Letter Country Code
          drawingDrawing Vector Data
2. test_simplified.csv - the test data in the simplified vector format
3. train_raw.zip - the training data in the raw vector format; one csv file per word
4. train_simplified.zip - the training data in the simplified vector format; one csv file per word

These datasets are provided by Google AI on Kaggle competition website. 

### Solution Statement
_(approx. 1 paragraph)_

In this section, clearly describe a solution to the problem. The solution should be applicable to the project domain and appropriate for the dataset(s) or input(s) given. Additionally, describe the solution thoroughly such that it is clear that the solution is quantifiable (the solution can be expressed in mathematical or logical terms) , measurable (the solution can be measured by some metric and clearly observed), and replicable (the solution can be reproduced and occurs more than once).

### Benchmark Model
_(approximately 1-2 paragraphs)_

In this section, provide the details for a benchmark model or result that relates to the domain, problem statement, and intended solution. Ideally, the benchmark model or result contextualizes existing methods or known information in the domain and problem given, which could then be objectively compared to the solution. Describe how the benchmark model or result is measurable (can be measured by some metric and clearly observed) with thorough detail.
