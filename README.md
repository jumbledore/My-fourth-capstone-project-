# My fourth capstone project

### Gender voice recognition by voice and speech analysis

![Screenshot of dashboard](https://github.com/jumbledore/My-fourth-capstone-project-/assets/123168272/fdb3c412-9ab2-4d73-9742-7f5010ffe0eb)

#### Description of dataset

Dataset consists of 3,168 recorded voice samples, collected from male and female speakers. The voice samples are pre-processed by acoustic analysis in R using the seewave and tuneR packages, with an analyzed frequency range of 0hz-280hz (human vocal range).

#### General observations

- Both models have an F1 score of higher than 0.7; both models used will be good to help distinguish voice gender based on voice and speech data.
- CNN has a higher precision, recall and F1 score of 0.98; for the purpose of the data used, it is a better model.

### Addtional work done (convereting data into a picture and using CNN model for gender voice recognition)

#Original data
![Screenshot of original data](https://github.com/jumbledore/My-fourth-capstone-project-/assets/123168272/8e061c22-5914-4b00-9c5c-0009eabf14f7)

The above data has 20 columns. To make it into a picture, we have to make the data into a (5*5) frame; add 5 more columns.

#Data with added 5 empty columns

![Screeenshot of original data with 5 additional empty columns](https://github.com/jumbledore/My-fourth-capstone-project-/assets/123168272/283ac81a-410c-4c5b-9fc5-f384b8f2c336)


#Results

![Screenshot of data in image form](https://github.com/jumbledore/My-fourth-capstone-project-/assets/123168272/3021247a-b664-414d-9541-56e89fe72300)

# Heatmap and classification report using CNN model

![Heatmap and classification report based on CNN model](https://github.com/jumbledore/My-fourth-capstone-project-/assets/123168272/1abd1055-2c8d-41af-83ba-9fecc6e266b3)

#### Insights
- Data presented in a picture using CNN model (X) has a slightly lower F1 score compared to CNN model trained on raw data; this is due to additional inputs of empty data that has no correlation.
- X still has a high F1 score of 0.97 which meant that the model is also useful in helping to distinguish gender based on data presented in a picture.
- Based on the F1 scores of all 3 models, it strongly suggests that male and female voice can be distinguished based on the data provided.

[Link to LinkedIn](https://www.linkedin.com/in/jeremy-tay-116124139/)
