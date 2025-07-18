# YouTube Data Analysis with Python

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Notebooks](#notebooks)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Description
This repository contains Jupyter Notebooks that demonstrate how to collect and analyze YouTube channel and video data using the YouTube Data API. The notebooks focus on fetching channel statistics, video details, and comments, and performing exploratory data analysis (EDA) to understand video performance metrics, content distribution, and upload patterns. The analysis includes visualizations such as bar plots, scatter plots, histograms, and word clouds.

## Installation
To run the notebooks, you need to have Python installed along with the following libraries:
- `googleapiclient`
- `pandas`
- `seaborn`
- `matplotlib`
- `isodate`
- `nltk` (for word cloud, though there might be issues with font support)

You can install these libraries using pip:
```bash
pip install googleapiclient pandas seaborn matplotlib isodate nltk
```

Additionally, you need a YouTube Data API key, which you can obtain by following the instructions on the [Google Developers Console](https://console.developers.google.com/).

## Usage
1. Obtain a YouTube Data API key from the Google Developers Console.
2. Replace the `api_key` variable in the notebooks with your own API key.
3. Open the notebooks in Jupyter Notebook or Google Colab.
4. Run the cells step by step to execute the code and generate the visualizations.

**Note**: Some parts of the notebooks, such as the word cloud in `main3.ipynb`, may encounter errors due to font support issues or network problems (e.g., NLTK download errors). Ensure you have the required fonts installed or adjust the code as needed.

## Notebooks
- **`main3.ipynb`**:
  - Collects data for four specific channels: "NeuralNine", "techTFQ", "Thu Vu data analytics", and "BLADE RUNNER".
  - Performs data cleaning and preprocessing.
  - Conducts EDA to analyze video performance (e.g., views, likes, comments), content distribution, and upload schedules.
  - Includes visualizations such as bar plots for best/worst-performing videos, scatter plots for views vs. likes/comments, histograms for video duration, and a word cloud for video titles (though the word cloud may have errors).

- **`main4.ipynb`**:
  - Collects data for multiple channels, including "techTFQ", "BLADE RUNNER", "Thu Vu data analytics", "Python Simplified", "NeuralNine", "Kylie Ying", and "TheFakeWeeb".
  - Performs a detailed analysis of the "NeuralNine" channel, including identifying top-performing videos and visualizing monthly video publication trends.
  - Exports video details for "NeuralNine" to CSV and Excel formats.

## Results
- **Channel Statistics**:
  - Subscriber counts, total views, and video counts for multiple channels.
  - For example, "NeuralNine" has 237,000 subscribers, 15,686,730 views, and 590 videos.

- **Video Performance**:
  - Top-performing videos for "NeuralNine" include "Modern Graphical User Interfaces in Python" (865,446 views) and "Intelligent AI Chatbot in Python" (757,465 views).
  - Monthly video publication trends for "NeuralNine" show variability, with November and December having the highest uploads (73 and 70 videos, respectively).

- **Visualizations**:
  - Bar plots comparing channels by subscribers, views, and total videos.
  - Scatter plots showing correlations between views, likes, and comments.
  - Histograms for video duration distribution.
  - A word cloud for video titles (with potential errors in `main3.ipynb`).

## Contributing
Contributions are welcome! If you have suggestions for improvement or want to add more features, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact
If you have any questions or need further assistance, please contact me at [your email address].