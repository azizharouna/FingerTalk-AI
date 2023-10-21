# FingerTalk-AI
AI translating American Sign Language fingerspelling into text. Trained on 3M+ characters from 100+ Deaf signers, this tool aims to make tech more accessible for the Deaf/Hard of Hearing community. Enhancing communication &amp; bridging gaps, one sign at a time

## 1. Objective
- Detect and translate ASL fingerspelling into text using a dataset of over three million fingerspelled characters thanks to google initiative!

## 2. Data Understanding
- **Initial Exploration**: Open the dataset and check its structure, data types, and missing values.
- **Visualization**: Display random samples to get an insight into the quality and variety of images.
- **Distribution Analysis**: Check for class imbalances among fingerspelled characters.

## 3. Data Preprocessing
- **Cleaning**: Address missing or corrupted data.
- **Normalization**: Standardize image sizes, possibly convert to grayscale or normalize pixel values.
- **Augmentation**: Use techniques rotation, zooming, and flipping to artificially enhance the dataset.
- **Splitting**: Divide the data into training, validation, and test sets.

## 4. Feature Engineering
- **Feature Extraction**: using pre-trained models extract features from one of the intermediate layers.
- **Dimensionality Reduction**: If necessary, use PCA or t-SNE for visualization or to reduce feature space.

## 5. Modeling
- **Baseline Model**: Create a simple model (shallow CNN) to set a performance baseline.
- **Complex Models**: Explore deeper architectures or use pre-trained models (ResNet) 
- **Hyperparameter Tuning**: Use grid search or random search to optimize model parameters.

## 6. Evaluation
- **Metrics**: Use accuracy, F1 score, and confusion matrix to evaluate performance.
- **Validation**: Regularly check the model's performance on the validation set to prevent overfitting.
- **Error Analysis**: Visualize false positives and negatives to understand common mistakes.

## 7. Optimization
- **Model Refinement**: Based on evaluation, refine the model architecture or training strategy.
- **Ensembling**: Combine predictions from multiple models for better accuracy.

## 8. Deployment
- **Model Export**:
- **Integration**: Integrate the model into server/app
- **Monitoring**: Implement tools to monitor the model's performance in real-time.

## 9. Feedback
- **User Testing**: (TBD)
- **Iteration**: Continuously improve the model based on real-world feedback.

## 10. Documentation
- **Code**: 
- **Results**: 
