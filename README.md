# Methodology

Following steps have been implemented to determine the authenticity of brand logos:

- **Logo Input:** This is the input module of the system, where logos are submitted for
analysis. These logos may come from a given kaggle dataset.
- **Data Preprocessing:** In this module, the logos are preprocessed and prepared for
analysis. This may involve resizing the logos to a standard size, removing
background noise or clutter, or performing other preprocessing steps to improve the
quality of the logo for analysis.
- **Feature Extraction:** In this module, the system extracts relevant features from the
logo that will be used for analysis. These features include colour, shape, typography,
and other characteristics of the logo.
- **Deep Learning Model:** This is the core of the system, where a deep learning model
CNN is used to analyze the features of the logo and compare them to a database of
known legitimate logos. The model is trained to recognize patterns in the features of
the logo that are indicative of authenticity.
- **Decision Making:** Based on the output of the CNN model, the system makes a
decision about the authenticity of the logo. If the logo is determined to be fake, it is
flagged for further review or removed from the system.
- **Output:** The final output of the system is a decision about the authenticity of the logo,
along with any relevant information or recommendations for further action. This output
may be presented to a user or incorporated into other systems or processes
