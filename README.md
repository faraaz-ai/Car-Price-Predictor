## Car Price Predictor

A web application to predict the price of used cars based on various input features. This project utilizes machine learning for prediction and is built with Python and Streamlit for an interactive user interface.

## Features

- User-friendly Interface**: Interactive sliders and dropdowns to input car details.
- Prediction**: Provides estimated car prices based on user inputs.
- Customizable**: Easily extendable to include more features or improve the model.

## Technologies Used

- **Programming Languages**: Python
- **Libraries**:
  - pandas
  - numpy
  - streamlit
  - pickle
- **Machine Learning**: Pretrained model serialized with pickle

## Dataset

The car dataset (Cardetails.csv) contains features such as:
- Car brand
- Manufacturing year
- Kilometers driven
- Fuel type
- Seller type
- Transmission type
- Ownership history
- Mileage
- Engine capacity
- Maximum power
- Number of seats

## Application Flow

1. **Input Features**: Users provide car details through an interactive Streamlit interface.
2. **Data Transformation**: Input data is encoded and transformed to match the model's requirements.
3. **Model Prediction**: The pre-trained model predicts the car's price.
4. **Output**: The estimated price is displayed to the user.

## Installation

1. Clone the repository:
   git clone https://github.com/your-username/Car-Price-Predictor.git
   cd Car-Price-Predictor
   ```
2. Install dependencies:
   pip install -r requirements.txt
   ```
3. Run the application:
   streamlit run app.py
   ```

## Usage

1. Open the application in your browser.
2. Select car details such as brand, manufacturing year, kilometers driven, fuel type, etc.
3. Click the **Predict** button to get the estimated price.

## File Structure

- `app.py`: Streamlit application script.
- `Car_Price_Model.ipynb`: Notebook for training and evaluating the machine learning model.
- `Cardetails.csv`: Dataset used for training.
- `model.pkl`: Serialized machine learning model.

## Future Improvements

- Add more features to improve prediction accuracy.
- Enhance the user interface with additional visualizations.
- Deploy the application on a cloud platform like AWS or Heroku.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.


Enjoy predicting car prices with the Car Price Predictor!

