# Movie Recommender System

This repository contains the source code for a Movie Recommender System implemented as a Streamlit web application. The system recommends movies based on user-selected movies and utilizes The Movie Database (TMDb) API to fetch movie data, including posters and details. Here's how to set up and use this Movie Recommender System:

## Features

- **Background Image:** The application has a customizable background image, making it visually appealing.

- **Movie Recommendations:** Users can select a movie from a dropdown list and click a button to receive movie recommendations based on their selection.

- **Movie Details:** The recommendations include movie names, posters, and links to detailed information on themoviedb.org.

## Setup

1. **Clone the Repository:** Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your-username/movie-recommender.git
   ```

2. **Install Required Packages:**

   Navigate to the project directory and install the necessary Python packages:

   ```bash
   pip install streamlit requests
   ```

3. **Data Files:**

   This project requires two data files, `movie_list.pkl` and `similarity.pkl`, to function properly. These files likely contain movie information and similarity scores. Make sure you have access to these files or generate them if necessary.

4. **Background Image (Optional):**

   If you want to change the background image, replace `background2.jpg` in the project directory with your desired background image. The `add_bg_from_local` function in the code will handle setting the background.

## Usage

1. **Running the Streamlit App:**

   Save the provided code in a Python file, for example, `movie_recommender.py`.

2. **Running the Streamlit App Locally:**

   Open your terminal or command prompt, navigate to the directory containing `movie_recommender.py`, and run the Streamlit app using the following command:

   ```bash
   streamlit run app.py
   ```

3. **Accessing the App:**

   After running the Streamlit app, it will provide a local development server address (e.g., http://localhost:8501) in your terminal. Open a web browser and go to that address to access the Movie Recommender System.

4. **Using the App:**

   - You will see a dropdown list where you can type or select a movie.
   - Click the "Show Recommendation" button to receive movie recommendations based on your selection.
   - The recommendations will include movie names, posters, and links to detailed information on themoviedb.org.

## Customization

You can customize the background image and make further modifications to the code to suit your preferences or requirements. The code provided here serves as a starting point, and you can extend it as needed.

## Contributions

Contributions to this Movie Recommender System project are welcome! If you have ideas for improvements or new features, please feel free to submit issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

---

Enjoy using the Movie Recommender System! If you encounter any issues or have questions, please don't hesitate to reach out for assistance.
