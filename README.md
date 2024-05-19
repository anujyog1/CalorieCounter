# CalorieCounter

CalorieCounter is a simple Python-based application designed to help users track their daily caloric intake. It is built using Streamlit, providing an easy-to-use interface for monitoring calories.

## Features

- **Calorie Tracking**: Tracks and displays daily caloric intake.
- **Gemini Pro Integration**: Utilizes Gemini Pro for advanced features.
- **Google API Integration**: Utilizes Google API for additional functionalities.

## Requirements

To run this project, you need to have Python installed along with the following libraries:

- Streamlit
- Gemini Pro
- Google API Client

You can install these requirements using the following command:
```
pip install -r requirements.txt
```

## Installation

1. **Clone the repository**:
    ```
    git clone https://github.com/shradha-2022/CalorieCounter.git
    ```
2. **Navigate to the project directory**:
    ```
    cd CalorieCounter
    ```
3. **Create a virtual environment**:
    ```
    python -m venv venv
    ```
4. **Activate the virtual environment**:
    - On Windows:
        ```
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```
        source venv/bin/activate
        ```
5. **Install the required libraries**:
    ```
    pip install -r requirements.txt
    ```

6. **Set up the Google API Key**:
    - Obtain your Google API key from the [Google Cloud Console](https://console.cloud.google.com/).
    - Create a file named `.env` in the project directory.
    - Add the following line to the `.env` file:
        ```
        GOOGLE_API_KEY=your_google_api_key
        ```

7. **Set up the Gemini Pro API Key**:
    - Obtain your Gemini Pro API key from the [Gemini Pro Console](https://pro.gemini.com/).
    - Add the following line to the `.env` file:
        ```
        GEMINI_PRO_API_KEY=your_gemini_pro_api_key
        ```

8. **Run the application**:
    ```
    streamlit run app.py
    ```

## Usage

1. Open your terminal and run the application using `streamlit run app.py`.
2. Open your web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`).
3. Start tracking your daily caloric intake.

## Project Structure

```
CalorieCounter/
│
├── app.py              # Main application file
├── requirements.txt    # List of dependencies
├── .env                # Environment variables file for API keys
└── License.md          # License file
```

## Contributing

Contributions are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```
    git checkout -b feature-name
    ```
3. Make your changes and commit them:
    ```
    git commit -m "Add feature"
    ```
4. Push to the branch:
    ```
    git push origin feature-name
    ```
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [License.md](License.md) file for details.

## Acknowledgements

Special thanks to all contributors and users for their support.

---

For any issues or feature requests, please open an issue on GitHub.

---

Made with ❤️ by Shradha-2022

