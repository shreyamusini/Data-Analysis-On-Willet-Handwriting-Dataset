# Analysis-On-Willet-Handwriting-Dataset
  This project analyzes the accuracy of the classification of the letters of the English Alphabet from the neural data collected in the paper:  High-performance brain-to-text communication via handwriting.

  The Willett Handwriting Dataset contains neural data from a method that translates the thought of writing a certain character to text. This method was configured through a set of experiments done with individuals with impaired movement. The specific data used for this analysis is from a patient who was asked to imagine writing a letter or sentence. The neural data from these trials was later used to predict the letters/sentences that the patient thought about.

  In the BCI Workshop/Hackathon at UCSD, we took the t-SNE analyses and preliminary code of helper functions/downloading files provided in the Willett Handwriting Dataset Notebook to do further analysis of the efficacy of the classification through clustering. In the workshop, my group worked together to code the analyses. 

  The t-SNE analysis of the neural data and the labels of each letter showed some letters clustered very closely together. Through these clusters, we wondered if the characters were being correctly predicted because certain letters shared the same strokes to write. We investigated this question through the use of KMeans Clustering to see if the clusters correctly grouped each character into its own cluster and compared it with an LDA Classifier. 


# Packages/Technologies/Methods Used:
- KMeans
- LDA
- Matplotlib
- Pandas
- NumPy
- Seaborn
- Sklearn
- Coded in Python
- Scipy
- Confusion Matrix
