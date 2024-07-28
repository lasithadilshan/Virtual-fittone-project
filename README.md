---

# Virtual Fiton Project

## Project Overview
The Virtual Fiton Project aims to create a online cloth fiton platform. This project includes machine learning models for predictive analysis, a web interface for user interaction, and various resources for managing and enhancing user experience.

## Project Structure
The project is organized into several key directories and files:

- **fitone project resource files**
  - **Avatars list**: Contains avatar images and resources.
  - **datasets**: Stores datasets used for training machine learning models.
    - `model5.csv`: Dataset containing data for model training.
    - `shirt size.csv`: Dataset with information on shirt sizes.

- **ML models**: Includes machine learning model files and scripts.

- **pickel files**: Stores serialized machine learning models.
  - `predictor.pickle`: Pickle file containing the main predictor model.
  - `rfcpredictor3.pickle`: Pickle file containing another version of the predictor model.

- **venv**: Python virtual environment containing project dependencies.
  - `Include`, `Lib`, `Scripts`: Standard directories for Python virtual environments.

- **website**
  - **model**: Directory containing model files for the web application.
    - `predictor.pickle`: Pickle file used by the web application.
    - `rfcpredictor3.pickle`: Another pickle file for the web application.
  - **static**: Directory for static files like CSS, JavaScript, images, etc.
  - **templates**: Directory containing HTML templates for the web application.
    - `aboutus.html`: Page providing information about the project.
    - `help.html`: Help page for users.
    - `index_model1.html`: Main page template using the first model.
    - `index_model2.html`: Main page template using the second model.

- **app.py**: The main application file for running the web server and handling requests.

- **.gitignore**: File specifying untracked files to ignore in version control.

- **README.md**: This file provides an overview of the project and its structure.

- **requirements.txt**: Lists the Python dependencies required for the project.

## How to Run the Project
1. **Set up the virtual environment**:
   ```sh
   python -m venv venv
   ```

2. **Activate the virtual environment**:
   - On Windows:
     ```sh
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```sh
     source venv/bin/activate
     ```

3. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the application**:
   ```sh
   python website/app.py
   ```
   Open a web browser and navigate to `http://127.0.0.1:6001` to access the application.

## Contribution
If you wish to contribute to the project, please follow the guidelines outlined in the `CONTRIBUTING.md` file (if available). For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the `LICENSE.md` file for more details.

---