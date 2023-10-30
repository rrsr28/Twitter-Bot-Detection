# Twitter-Bot-Detection

The **Twitter Bot Detection** project is aimed at detecting and classifying Twitter bots, automated accounts that often engage in spam, misinformation, and manipulative activities on the platform. This project utilizes data analysis, machine learning classifiers, and Locality-Sensitive Hashing (LSH) to improve the accuracy of bot detection. By examining various account features like the number of followers, accounts followed, verification status, and the presence of real location information, we've developed a comprehensive approach to differentiate between bots and human-operated accounts.

## Features

- Data preprocessing to prepare the Twitter data for analysis.
- Utilization of diverse feature sets for accurate bot classification.
- Implementation of machine learning classifiers to predict and classify bot accounts.
- Deployment of Locality-Sensitive Hashing (LSH) for efficient and scalable similarity search.

## Datasets

The dataset used in this project is primarily derived from the research paper available at [[Link to the Paper]](https://www.mdpi.com/2071-1050/15/8/6662). It comprises a comprehensive collection of Twitter user profiles and tweets, meticulously curated and prepared for Twitter bot detection analysis. This dataset plays a central role in training machine learning models, conducting data analysis, and evaluating the performance of various bot detection techniques. Additionally, supplementary datasets, such as User and LocationData, have been manually curated to enrich the dataset for a more detailed investigation. The dataset is characterized by diverse content-specific features, making it a valuable resource for exploring the behavior of Twitter accounts and detecting bot activity in the digital landscape.

## Getting Started

To get started with this project, you'll need Python and several libraries for data analysis, machine learning, and LSH. Here are the basic steps:

1. Clone this repository to your local machine.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Explore the project's Jupyter notebooks to understand the data analysis and machine learning process.
4. Use the provided Python scripts to apply bot detection to your own Twitter data.

## Requirements

- You can use this requirements.txt file to install the necessary libraries.
- Please note that you might need to change/modify the versions.

## Acknowledgments

I would like to extend our sincere appreciation to the original creators of a significant portion of the dataset used in this project. Their efforts in preparing and sharing this portion of the dataset for research purposes have been invaluable in advancing our understanding of Twitter bot detection. (Check the 1st Reference) The collaborative nature of this project, involving both the original dataset and our contributions, has enhanced the quality of our research and findings.

## References
https://www.mdpi.com/2071-1050/15/8/6662

**Twitter Bot Detection** is developed and maintained by rrsr28.

