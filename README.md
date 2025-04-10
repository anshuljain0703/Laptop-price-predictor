# Laptop Price Predictor

This project is a **Laptop Price Predictor** built using **Machine Learning**. The application predicts laptop prices based on various features such as brand, processor, RAM, storage, and more. The model has been deployed using **Streamlit** for a user-friendly web interface.

## Features
- Predicts laptop prices based on user-provided specifications.
- Utilizes a trained machine learning pipeline for accurate results.
- Interactive web interface built with **Streamlit**.

## Installation

To run the project locally, follow these steps:

1. **Clone the Repository**
```bash
git clone https://github.com/anshuljain0703/laptop-price-predictor.git
cd laptop-price-predictor
```

2. **Install Dependencies**
```bash
pip install -r requirements.txt
```

3. **Download/Place the Model File (`pipe.pkl`)**
Ensure the `pipe.pkl` file is in the root directory or the correct path specified in `app.py`.

4. **Run the Application**
```bash
streamlit run app.py
```

5. **Access the Web Interface**
- Open [https://huggingface.co/spaces/Anshul-jain07/LaptopPricePredictor] in your browser.

## Dataset
The dataset includes features such as:
- Company  
- TypeName  
- Ram  
- Weight  
- Price  
- Touchscreen  
- Ips  
- PPI  
- Cpu brand  
- HDD  
- SSD  
- Gpu brand  
- os  

## Model Training
The model was trained using the following steps:
1. Data Cleaning and Preprocessing
2. Feature Engineering
3. Model Selection 


## Future Improvements
- Enhance the model with improved feature engineering.
- Add more interactive visualizations.
- Expand dataset to include more diverse laptop specifications.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for improvements or bug fixes.

## License
This project is licensed under the **MIT License**.

## Contact
For questions or feedback, please reach out at **anshuljain071103@gmail.com**

