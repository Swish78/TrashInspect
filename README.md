# TrashInspect

TrashInspect is a garbage classification project that utilizes a machine learning model for identifying and categorizing different types of waste. The project consists of a React frontend for user interaction and a FastAPI backend for serving predictions from the trained model.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (for running the React frontend)
- [Python](https://www.python.org/) (for running the FastAPI backend)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Swish78/TrashInspect.git
    cd TrashInspect
    ```

2. Install dependencies for the React frontend:

    ```bash
    cd frontend
    npm install
    ```

3. Install dependencies for the FastAPI backend (create a virtual environment first if desired):

    ```bash
    cd backend
    pip install -r requirements.txt
    ```

## Usage

1. Start the React frontend:

    ```bash
    cd frontend
    npm start
    ```

   The frontend will be accessible at [http://localhost:3000](http://localhost:5173).

2. Start the FastAPI backend:

    ```bash
    cd backend
    uvicorn main:app --reload
    ```

   The backend will be accessible at [http://localhost:8000](http://localhost:8000).

3. Open your web browser and navigate to the React frontend to interact with TrashInspect.

## Garbage Classification

TrashInspect classifies waste into the following 12 classes:

1. Paper
2. Cardboard
3. Biological
4. Metal
5. Plastic
6. Green Glass
7. Brown Glass
8. White Glass
9. Clothes
10. Shoes
11. Batteries
12. Trash

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or features you'd like to add.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to [Material-UI](https://mui.com/) for providing beautiful React components.
- The garbage classification model was trained using TensorFlow and Keras.

---
