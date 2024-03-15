


## React and FastAPI Project Deep Learning model

This project combines a React frontend with FastAPI backend for our project represents a significant advancement in the field of precision agriculture, offering a reliable and efficient tool for crop disease management and soil analysis. Through the integration of deep learning algorithms, we are paving the way for a more sustainable and productive future in agriculture..

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/shivampandey777/Visinory.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd visionary
    ```

3. **Install frontend dependencies:**
    ```bash
    npm install
    ```

4. **Install backend dependencies (Optional if not installed globally):**
    ```bash
    cd crop
    pip install -r requirements.txt
    cd ..
    cd soild
    pip install -r requirements.txt
    cd ..
    ```

## Usage

### Frontend

1. **Start the React development server:**
    ```bash
    npm start
    ```

2. Open your browser and go to `http://localhost:3000` to view the application.

### Backend

For the backend, make sure you have Python installed.

#### Crop API

1. **Navigate to the crop directory:**
    ```bash
    cd crop
    ```

2. **Run the FastAPI server:**
    ```bash
    python -m uvicorn main_crop:app --host 0.0.0.0 --port 8001 --reload
    ```

#### Soil API

1. **Navigate to the soil directory:**
    ```bash
    cd soild
    ```

2. **Run the FastAPI server:**
    ```bash
    python -m uvicorn main_soil:app --host 0.0.0.0 --port 8000 --reload
    ```

## Contributing

Contributions are welcome! Please feel free to open a pull request or submit an issue if you encounter any problems.

