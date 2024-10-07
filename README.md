# Diabetes_Globant_Challenge
Autor: Nicolás Hernández Zapata
This repository develops a challenge presented by globant on the identification of readmission of patients with diabetes.

# Organization
The repository is organized as follows:
* data: Contains the 3 datasets that are extracted from the original dataset.
* src: Contains the codes that are developed as the problem is analyzed.

## Work path

* Initially the repository is cloned and a careful reading is made of the Strack paper that provides a first approach to the dataset and the possible results.
* Based on the results of the paper, 3 datasets are proposed that are considered valuable to study. The first one corresponds to the dataset proposed in the paper where statistical independence is guaranteed. The second one takes into account all the visits of patients who were admitted more than once. The idea at this point is to find patterns of all their visits. Finally, an exclusive dataset is created for patients whose outcome was death.
* A detailed exploratory analysis is performed on the first dataset in order to find results that indicate/show the results obtained by Strack in his publication.
* A slightly less detailed analysis is performed on the second dataset, looking for patterns that are considered intuitive and if there is something very noticeable in sight.

So far it has been developed up to this point
## Next steps
* A study of the dead dataset will be carried out to look for patterns.
* Classification models will be proposed for the Strack dataset, initially with the objective of evaluating the importance of the features using the SHAP library.
* The Hernandez dataset can be used to predict the number of times a person will be readmitted to the hospital (it is an idea that depends on the rest of the results).
