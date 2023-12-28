# Accent Recognition with Sequential MFCC Features

This project addresses the challenge of accent diversity in English speech recognition systems, aiming to enhance their accuracy through the implementation of a supervised machine learning model. The model utilizes Sequential Mel-frequency cepstral coefficients (MFCC) features to classify speakers as either having an Indian or American English accent.

### Methodology
1. **Proposed Method:** Sequential MFCC features are extracted from audio signals to provide a unique perspective for accent identification.
2. **Dataset:** The dataset comprises 3-5 second audio clips from VCTK-corpus, categorized into training (80%) and testing (20%).
3. **Preprocessing:** To address data imbalances, oversampling is applied to the training set. Feature extraction involves calculating 20 MFCC coefficients for each audio file using the Librosa library.
4. **Feature Extraction:** Mel-frequency cepstral coefficients (MFCC) are calculated for each audio frame, and sequential concatenation of these features provides a robust input set for accent classification.
5. **Supervised Learning:** Various classifiers, including K-Nearest Neighbors, Support Vector Machines, Gaussian Mixture Models, Neural Networks, and Logistic Regression, are employed for accent classification.

### Results and Discussion
- **Evaluation Metrics:** Precision, recall, reject rate, and overall accuracy are used to evaluate classifier performance.
- **Top Performers:** Neural Networks, K-Nearest Neighbors, and Logistic Regression demonstrate superior performance, with Neural Networks emerging as the top classifier.

### Conclusion and Future Work
- **Promising Results:** Accent classification through Sequential MFCC features showcases promising results, with up to 95% accuracy.
- **Future Work:** Incorporating this classification into speech recognition systems, extending the model to diverse accents and dialects, and exploring Hidden Markov Models for classification are areas for future development.

### Note
- This project was developed during the IIIT Hyderabad Hackathon as part of the Qualcomm problem statement on Accent Detection.
- The evaluation criteria include accuracy scores, novelty in methodology or ideation, and the clarity of presentation.
