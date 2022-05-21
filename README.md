# Machine Learning: Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

This project uses the data they gathered to train two machine learning (ML) models that are intended to classify candidate exoplanets. 

## Models
### Two Techniques
- Logistic Regression (LR)
- Random Forest Classifier (RFC)

### Model Design Approach
- Build a base model using the original dataset and all its 40 features.
- Use the base model to evaluate feature importance, and filter the data to include relevant features only.
- Build a second model (select features model) using the filtered data.
- Tune the model parameters using *GridSearchCV*.
- Build the final model using the tuned parameters. 

## Conclusions
Logistic regression provided a slightly less accurate result than the Random Forest model. This came at the cost of time however, as the RF model took many times longer at the model tuning stage to achieve this result.
