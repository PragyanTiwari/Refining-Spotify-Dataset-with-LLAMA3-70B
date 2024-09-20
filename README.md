[![SpotifyLogo](https://cdn3.emoji.gg/emojis/SpotifyLogo.png)](https://emoji.gg/emoji/SpotifyLogo)
# Spotify Explicitness Classifier

## 🪼 Introduction

This project aims to rectify a data quality issue discovered within the 'Most Streamed Spotify Songs 2024' Kaggle dataset.The original dataset contained inaccuracies in the classification of track explicitness. To enhance the dataset's reliability and facilitate more accurate analysis, we've implemented a refined methodology to **reclassify** spotify track explicitness.

## 🗃️ About the Project

### 🎯 Objective
To rectify the misclassified explicitness labels in the Spotify dataset using advanced natural language processing techniques.

About the Methodology:
We used the LLaMA 3-70B language model through the Fireworks API to reclassify explicitness labels in the Spotify dataset. A Langchain chain was built to automate the process, and the model's natural language understanding capabilities were leveraged to accurately assess explicit content.

## 🏁 Conclusion

The project revealed a significant discrepancy between the original dataset and our reclassification results. We identified 1,082 misclassified tracks out of the total dataset. This finding underscores the importance of data verification and the potential of using advanced language models for data quality improvement in music datasets.

The refined dataset, which includes both the original and the newly classified explicitness labels, is now available on Kaggle.


For access to the refined dataset, visit: [Spotify Refined Explicitness Classified Dataset](https://www.kaggle.com/datasets/pragyantiwari/spotify-refined-explicity-classified-1)
