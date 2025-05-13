 **Plant Classification Based on Water Needs**


Project Description:

This project aims to develop a machine learning model capable of classifying plants based on their water requirements—categorized as Low, Medium, or High—using key environmental inputs. The classification is based on features such as sunlight exposure (in hours), watering frequency per week, and soil type. With growing concerns about sustainable water usage and efficient gardening practices, this project provides a data-driven solution to support better irrigation planning and resource conservation in both agricultural and domestic settings.

The dataset used comprises 100 samples, each including numerical data for sunlight hours and watering frequency, as well as categorical information for soil type. The target variable is the water need of each plant. To prepare the data for modeling, categorical variables were encoded using one-hot encoding, and the dataset was split into training and testing sets in an 80:20 ratio.

A Random Forest Classifier was selected due to its ability to handle both numerical and categorical data, its robustness against overfitting, and its capacity to provide feature importance. The model was evaluated using standard classification metrics—accuracy, precision, recall, and F1-score—along with a confusion matrix for deeper insight into its performance. The final model achieved an overall accuracy of 85%, demonstrating strong predictive capabilities.

Key insights were drawn from the model's feature importance analysis, revealing the most influential factors affecting plant water requirements. This not only enhances interpretability but also supports practical decision-making for plant care and irrigation strategies.

By leveraging machine learning, this project demonstrates a scalable and intelligent method to support water conservation while maintaining plant health, making it a valuable contribution to the fields of environmental science, smart agriculture, and AI-powered gardening solutions.

