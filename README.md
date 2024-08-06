# Speaker Identification

Speaker Identification is an advanced application designed to recognize speakers based on their voice data using machine learning techniques. This application leverages various classification algorithms and is deployed using Flask to provide a user-friendly interface.

## About This Application

Identifying speakers based on voice data is a critical task in various domains, including security, authentication, and personalized experiences. This application facilitates speaker identification by processing voice data through multiple machine learning models and selecting the most accurate one.

### Key Features

- **Voice Data Processing**: Normalizes and prepares voice data for accurate classification.
- **Machine Learning Models**: Implements various classification algorithms to identify speakers.
- **Model Evaluation**: Assesses model performance using metrics like AUC and accuracy.
- **User Interface**: Provides a web-based GUI for easy interaction with the application.

### Machine Learning Techniques

- **Decision Tree Classifier**: Applied for initial classification tasks.
- **K-Nearest Neighbors (KNN)**: Used for classification and evaluated for its accuracy.
- **Random Forest Classifier**: Achieved the highest accuracy among the models, demonstrating superior performance.

### Tech Stack

- **Machine Learning**:
    - **Normalization**: Pre-processes voice data to improve model performance.
    - **Decision Tree Classifier**: For initial classification.
    - **KNN Classification**: For evaluating speaker identity.
    - **Random Forest Classifier**: Provides the highest accuracy for speaker identification.
- **Flask**: Utilized for deploying the application and creating a user-friendly web interface.
- **Python**: The programming language used for machine learning and Flask development.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- scikit-learn
- Other Python libraries for machine learning and data processing (e.g., NumPy, pandas)

### Installation

1. **Clone the Repository**:
    
    ```bash
    
    git clone https://github.com/yourusername/Speaker_Identification.git
    cd Speaker_Identification
    
    ```
    
2. **Install Dependencies**:
    
    ```bash
    
    pip install -r requirements.txt
    
    ```
    

### Usage

1. **Run the Flask Application**:
    
    ```bash
    
    python app.py
    
    ```
    
2. **Access the Web Interface**:
    - Open a web browser and navigate to `http://127.0.0.1:5000` to interact with the application.
3. **Upload Voice Data**:
    - Use the web interface to upload voice recordings for speaker identification.
4. **View Results**:
    - The application will process the voice data using the Random Forest Classifier and display the identified speaker along with the classification results.

## Model Performance

- **Random Forest Classifier**: Achieved the highest accuracy of 72%.
- **Decision Tree Classifier**: Provides a baseline for comparison.
- **KNN Classification**: Evaluated for its classification accuracy.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions or suggestions, please contact us at pavi2468kuk@gmail.com
