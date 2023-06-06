# CodingNightEscapeRom-LastChallenge

Last Challenge: The Hidden Chamber

# Description:
In this challenge, you will be provided with a dataset containing information about various artifacts and their attributes. Your task is to use data analysis and coding skills to identify patterns, filter the data based on specific criteria, and uncover the location of a stolen artifact along with passcode.

# Input
You will be given input in a csv file with attributes

Scenario 1:
ArtifactName|Location|UniqueIdentifier|Value|HistoricalSignificance|LostSince
|--|--|--|--|--|--|
Sculpture|London|8987|1000|High|
Painting|Paris|7658|5000|Medium|
Pottery|Singapore|7678|200|Low|
Jewelry|Afghanistan|6547|3000|High|2023-05-15

Scenario 2:
ArtifactName|Location|UniqueIdentifier|Value|HistoricalSignificance|LostSince
|--|--|--|--|--|--|
Sculpture|London|8987|1000|High|
Painting|Paris|7658|5000|Medium|2018-05-10
Pottery|Singapore|7678|200|Low|
Jewelry|Afghanistan|6547|3000|High|2022-05-15

You need to find the lost artifact based on below criteria
- The artifact is lost recently
- The lost artifact has high significance but if multiple artifacts are lost then an artifact with high value but low or medium significance can be the lost artifact

# Output:
Scenario 1:
- Location: Afghanistan Passcode: 6547

Scenario 2:
- Location: Paris Passcode: 7658

**Hint:
You can consider using Python libraries like Pandas to load and manipulate the dataset efficiently. You can leverage functions such as filtering, grouping, or sorting to extract relevant information and make informed decisions.

# Dataset
[dataset.csv]()
