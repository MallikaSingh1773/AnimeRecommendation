# Anime Recommendation System

This is an Anime Recommendation System that uses both **Collaborative Filtering** and **Content-Based Filtering** to suggest anime to users. The project is built using **Python**, **Pandas**, **Scikit-Learn**, and **Streamlit** for the frontend. Users can choose between different filtering techniques to get personalized anime recommendations.

## Features
- **Collaborative Filtering**: Recommends anime based on user interactions.
- **Content-Based Filtering**: Suggests anime based on similarity in features like genre, description, etc.
- **Interactive UI with Streamlit**: Users can choose the recommendation type and get instant results.

## Dataset Setup
This project uses CSV files that are not stored in the GitHub repository due to size constraints. You need to download the dataset from **Google Drive** and place it in the project directory.

### Steps to Set Up the Dataset
1. **Download the Dataset:**
   - Click on this link: [Anime Dataset](https://drive.google.com/file/d/1vZs0TDthO0qSKblMyAFYYhAw0AOZp1_2/view?usp=sharing)
   - Download the CSV files to your local machine.

2. **Move the Files:**
   - Place the downloaded CSV files inside your project directory (you can organize them as per your preference).

3. **Verify the File Structure:**
   Ensure the dataset files are accessible within your project, such as:
   ```
   AnimeRecommendation/
   ├── anime2.py
   ├── anime_recommendation.ipynb
   ├── app.py
   ├── app2.py
   ├── popular_anime.csv
   ├── recom.ipynb
   ├── requirements.txt
   ├── README.md
   ```

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/MallikaSingh1773/AnimeRecommendation.git
   cd AnimeRecommendation
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv env
   source env/bin/activate  # For Mac/Linux
   env\Scripts\activate  # For Windows
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Running the Application
1. Ensure the dataset is properly set up as mentioned above.
2. Run the Streamlit application:
   ```sh
   streamlit run app.py
   ```
3. Open the local URL provided by Streamlit in your browser.
4. Select a filtering method and get anime recommendations!

## Folder Structure
```
AnimeRecommendation/
├── anime2.py               # Additional script
├── anime_recommendation.ipynb # Jupyter notebook for testing
├── app.py                 # Main Streamlit application
├── app2.py                # Additional app script
├── popular_anime.csv       # Sample dataset
├── recom.ipynb            # Recommendation system notebook
├── requirements.txt       # Dependencies
├── README.md              # Project documentation
```

## Contributing
If you want to contribute, feel free to fork the repo, create a new branch, and submit a pull request.

## Contact
For any issues or suggestions, reach out via GitHub issues.

Happy coding! 😊

