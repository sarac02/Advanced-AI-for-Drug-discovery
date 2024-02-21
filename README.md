# Advanced-AI-for-Drug-discovery
This repository contains Python code for analyzing and exploring genomic data related to the SARS coronavirus (SARS-CoV-2). The code utilizes various machine learning techniques, including PCA (Principal Component Analysis) and K-means clustering, to uncover patterns and insights from genomic sequences and alignment hit data.

## Genomic Sequence Analysis
### Length Analysis
Added a 'Length' column to the genomic sequence dataframe. <br>
Filtered rows to keep only those with the median sequence length. <br>
### Substring Matching
Created a 'Match?' column indicating whether each sequence contains a specific substring. <br>
### Sequence Differences
Calculated the number of differences between genomic sequences and identified the most similar pair.<br>
### PCA and K-means Clustering
Applied PCA to alignment hit data to visualize similarity and reduce dimensions.<br>
Performed K-means clustering on numeric columns and visualized clusters using PCA.<br>
## Alignment Hit Analysis
### Data Exploration
Loaded alignment hit data and performed basic exploratory data analysis.<br>
Visualized correlations between numeric features using a heatmap.<br>
### PCA and K-means Clustering
Applied PCA to numeric columns and visualized principal components.<br>
Conducted K-means clustering and visualized clusters using scatter plots.<br>
### Predictive Modeling
Linear Regression and Neural Network<br>
Predicted 'bit_score' using linear regression.<br>
Implemented a neural network regression model with three hidden layers and evaluated its performance.<br>

## Dependencies
pandas<br>
numpy<br>
scikit-learn<br>
matplotlib<br>
seaborn<br>

## License
This project is licensed under the MIT License - see the LICENSE file for details.<br>

## Data sources: 
SARS_CORONAVIRUS_NC_045512_sequence.fasta, Alignment-HitTable.csv<br>
