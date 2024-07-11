# Movie Recommender System

![Demo](./recording.gif)

## Project Overview

This project is a Movie Recommender System that allows users to select a movie from a dropdown menu and receive recommendations for similar movies. The system is built using various machine learning techniques and leverages the TMDB movie metadata dataset for generating recommendations.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **User-Friendly Interface**: Simple and intuitive interface to get movie recommendations.
- **Machine Learning**: Utilizes machine learning algorithms to find similarities between movies.
- **Scalability**: Can be extended to include more features and handle larger datasets.

## Dataset

The dataset used in this project is the [TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) from Kaggle. It contains detailed information about movies, including metadata such as genres, cast, crew, and keywords.

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shivang-Patel/Movie-Recommendor-System.git
   cd files
   ```


2. **Download the dataset**:
   Download the dataset from [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) and place it in the `data/` directory.

## Usage

1. **Run the Jupyter notebook**:
   Open and run the `Movie_Recommender.ipynb` file to train the model and generate recommendations.

2. **Start the application**:
   ```bash
   streamlit run app.py
   ```

3. **Get recommendations**:
   Select a movie from the dropdown menu and click "Recommend" to get a list of similar movies.

## Demo

Here is a short video demonstration of the Movie Recommender System in action:

![recording](https://github.com/Shivang-Patel/Movie-Recommendor-System/assets/106246165/e182e592-2962-4dd5-a9b4-f2c24fa33ece)


## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please contact me at [shivang.patel2303@gmail.com](mailto:shivang.patel2303@gmail.com).
