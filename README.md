# Movie Recommender System 🎬

This Movie Recommender System is designed for movie lovers who want to discover films similar to the ones they already enjoy. Built using powerful machine learning techniques, this system provides personalized recommendations by analyzing movie content and similarities.

## Dataset 
-  https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
  
## Features
- Recommends movies based on your favorite movie.
- Utilizes vectorization and cosine similarity for identifying movie similarities.
- Interactive web app built with Streamlit for a seamless user experience.

## Technologies Used
- **Python:** Core programming language.
- **Libraries:**
  - **Numpy:** For numerical operations and data manipulation.
  - **Pandas:** For data handling and preprocessing.
  - **Scikit-learn:** For implementing machine learning algorithms.
  - **NLTK (Natural Language Toolkit):** For text processing and cleaning.
  - **Streamlit:** Framework for building and deploying the web app.

## How It Works
The system compares the textual information of movies (like plot summaries) to compute their similarity. It uses vectorization techniques to convert text into numerical vectors and calculates similarity between movies using cosine similarity. The higher the similarity score, the more relevant the recommended movies.

## Installation & Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/VivekShinde7/Movie-Recommendation-System
    ```

2. Navigate to the project directory:
    ```bash
    cd Movie-Recommendation-System
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```
   The web app will be accessible at `http://localhost:8501`.

## Dataset
The dataset used for this project consists of movie metadata like title, genre, plot, and ratings. You can use any publicly available movie dataset or scrape data from movie databases like IMDb.

## Usage
1. Open the web app.
2. Enter the name of a movie you like.
3. The system will provide a list of similar movies based on content similarity.

## Future Enhancements
- Adding user-based collaborative filtering for personalized recommendations.
- Implementing advanced NLP techniques like TF-IDF or BERT for better accuracy.
- Improving the user interface for a more interactive experience.

## Contributing
Feel free to fork the repository, make improvements, and submit a pull request. Contributions are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
