# SMS-Spam-Prediction
Sure! Here's a draft for your README file:

---

# SMS Spam Detection

This project focuses on detecting spam messages using various machine learning models. The models were trained on the NUS SMS Spam Collection Dataset and evaluated on a generated dataset to assess their performance.

## Dataset

### NUS SMS Spam Collection Dataset
- **Spam messages**: ~1,000
- **Ham messages**: ~5,000
- **Imbalance**: The dataset is biased towards ham messages, impacting model performance.

## Models and Performance

### NUS Dataset
- **Random Forest**: 97% accuracy
- **Support Vector Machine (SVM)**: 97% accuracy
- **Multinomial Naive Bayes**: 96% accuracy

### Generated Dataset
- **Random Forest**: 41% accuracy
- **Support Vector Machine (SVM)**: 41% accuracy
- **Multinomial Naive Bayes**: 41% accuracy

The significant drop in accuracy when applying models trained on the NUS dataset to the generated dataset highlights the limitations of using older datasets. This underscores the need for updated training data to improve model performance on newer and more diverse inputs.

## Conclusion

The results demonstrate the importance of using up-to-date and diverse datasets for training machine learning models. Continuous updates and improvements in training data are essential for maintaining high model performance in real-world applications.

