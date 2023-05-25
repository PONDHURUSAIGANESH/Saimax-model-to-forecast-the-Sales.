# Sarimax-model-to-forecast-the-Sales.
Sales Prediction
Sample images
![Screenshot 2023-05-25 204517](https://github.com/PONDHURUSAIGANESH/Saimax-model-to-forecast-the-Sales./assets/78872384/f883ad60-ec86-4de4-8a25-3a626915ba20)
![Screenshot 2023-05-25 204137](https://github.com/PONDHURUSAIGANESH/Saimax-model-to-forecast-the-Sales./assets/78872384/0ee59547-198a-471f-a164-472cbda2078c)
![Screenshot 2023-05-25 204121](https://github.com/PONDHURUSAIGANESH/Saimax-model-to-forecast-the-Sales./assets/78872384/e21da25f-f6f9-414b-9c86-1075da00333e)

![Screenshot 2023-05-25 204331](https://github.com/PONDHURUSAIGANESH/Saimax-model-to-forecast-the-Sales./assets/78872384/a647750c-2f8c-4b23-b99c-f23f96b14700)
![Screenshot 2023-05-25 204347](https://github.com/PONDHURUSAIGANESH/Saimax-model-to-forecast-the-Sales./assets/78872384/1212a2ba-0857-4206-be3a-985b902833d7)
Tech stack that I used in this project

![Screenshot 2023-03-02 101029](https://github.com/PONDHURUSAIGANESH/Saimax-model-to-forecast-the-Sales./assets/78872384/5948d067-bcc0-4862-afca-124249b9811a)

# Sales Forecasting using SARIMAX Model

This project implements a Sales Forecasting system using the SARIMAX model. The system consists of a frontend built with Angular, a middleware backend using Flask, and Python for data processing. The predicted sales data can be downloaded, and the results can be visualized in Power BI.

## Features

- SARIMAX model for accurate sales forecasting
- Angular frontend for an intuitive user interface
- Flask backend for data processing and serving the API
- Python for implementing the SARIMAX model and data manipulation
- Downloadable prediction results
- Integration with Power BI for data visualization

## Technologies Used

- Angular
- Flask
- Python
- Power BI

## Prerequisites

Make sure you have the following installed:

- Angular CLI
- Python
- Flask

## Installation and Setup

1. Clone the repository:

git clone https://github.com/your-username/sales-forecasting.git

2. Navigate to the project directory:

```bash
cd sales-forecasting
```

3. Install frontend dependencies:

```bash
cd frontend
npm install
```

4. Install backend dependencies:

```bash
cd ../backend
pip install -r requirements.txt
```

5. Start the frontend server:

```bash
ng serve
```

6. Start the backend server:

```bash
python app.py
```

7. Open your browser and visit [http://localhost:4200](http://localhost:4200) to access the Sales Forecasting application.
## MongoDB Integration

This project utilizes MongoDB as the database for storing the sales data. MongoDB offers a flexible and scalable solution for data storage and retrieval.

### Prerequisites

Make sure you have MongoDB installed and running on your system. You can download MongoDB from the official website: [link to MongoDB website](https://www.mongodb.com/)

### Configuration

To connect the Flask backend with MongoDB, follow these steps:

1. Open the `config.py` file in the backend directory.

2. Update the MongoDB connection settings with your MongoDB credentials:

   ```python
   MONGO_URI = 'mongodb://<username>:<password>@<host>:<port>/<database>'


## Usage

1. Upload the sales data file to the application.
2. Configure the SARIMAX model parameters.
3. Initiate the sales forecasting process.
4. Once the forecasting is complete, download the prediction results.
5. Use Power BI to import and visualize the downloaded data.


## License

This project is licensed under the [MIT License](LICENSE).

```

Feel free to customize and add more information specific to your project, such as detailed instructions, screenshots, or additional sections about the project architecture or implementation details.
