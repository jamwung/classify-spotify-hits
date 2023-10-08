# Leveraging Explainable AI on Spotify Tracks
![Header](Images/Title.png)

Welcome to the `classify-spotify-hits` repository!

Here you can explore the technical report titled "Unlocking the Secrets Music Producers Don't Want You To Know." This project focuses on the implementation of Explainable AI using machine learning techniques on Spotify song data, with the main notebook being `01_ML2_Project_Main.ipynb`.

## Summary

In the world of music, an artist's reputation and popularity undoubtedly influence a song's success. However, numerous other factors contribute to a song's hit potential. This project aimed to create a machine learning model capable of predicting hit songs based on their features. Leveraging the Spotify API, our team collected data on songs from the years 2010 to 2019 and developed a machine learning model that achieved an impressive accuracy.

Using SHAP, we identified the top three most influential features for the model's predictions, namely instrumentalness, energy, and danceability. Additionally, we utilized the DiceML library to generate counterfactuals for songs that didn't perform well, allowing us to determine how minimal changes to a song's features could potentially turn it into a hit.

## Dataset
This project utilizes the [The Spotify Hit Predictor Dataset (1960-2019)](https://www.kaggle.com/datasets/theoverman/the-spotify-hit-predictor-dataset) from Kaggle containing features of each track and artist segmented by their decade of release.

## Practical Applications

This machine learning model can be a valuable tool for artists, record labels, streaming platforms, and advertisers, enabling them to make more informed decisions in the music industry. Potential future work could involve refining the definition of the prediction target and incorporating artist popularity as an additional feature for model predictions.

## Conclusion

In summary, this study provides valuable insights into the features that contribute to a song's success. By offering a practical decision-making tool, it enhances the capabilities of stakeholders within the music industry. Feel free to explore the project, run the notebooks, and leverage the model for your own analyses or applications.

Thank you for visiting our repository!

## Installation

To install the required dependencies, you can use `pip` with the provided `requirements.txt` file. Run the following command in your project environment:

```bash
pip install -r requirements.txt
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
