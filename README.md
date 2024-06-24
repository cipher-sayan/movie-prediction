# Movie Recommendation System

This project is a movie recommendation system built using Python and Streamlit. It leverages content-based filtering to recommend movies to users. The system utilizes the TMDB dataset to train the model and provide recommendations.

## Deployment

The application is deployed and can be accessed [here](https://sayan-movie-recommendation.streamlit.app/).

## Features

- **Movie Recommendations**: Provides movie recommendations based on user input.
- **Content-Based Filtering**: Utilizes content-based filtering techniques to suggest similar movies.
- **Interactive Web App**: Built with Streamlit for an intuitive and interactive user experience.
- **Engaging User Interface**: Fetches movie posters through an API to enhance the user experience.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/movie-recommendation-system.git
    ```
2. Navigate to the project directory:
    ```sh
    cd movie-recommendation-system
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
4. Run the Streamlit app:
    ```sh
    streamlit run app.py
    ```

## Usage

1. Open the web app in your browser.
2. Enter or select a movie name in the search box.
3. The system will recommend movies similar to the one you entered.
4. Enjoy the movie recommendations and explore new films!

## Dataset

The system utilizes the TMDB dataset to train the model. The dataset contains information about various movies, including metadata such as genres, actors, and plot summaries.

## How It Works

1. **Content-Based Filtering**: The system uses content-based filtering techniques to analyze the metadata of movies. It calculates the similarity between movies based on their content and recommends movies that are similar to the user's input.
2. **API Integration**: The app fetches movie posters using an external API to provide a visually engaging experience for the user.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or create a pull request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Streamlit](https://www.streamlit.io/) for providing an excellent framework for building web apps.
- [TMDB](https://www.themoviedb.org/) for the dataset and API support.
