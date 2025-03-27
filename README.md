Consumer Segmentation and Analysis


Project Synopsis

The research delves into customer segmentation with data clustering and classification.
The application is run on Streamlit, providing users with the tools to analyze customers'
spending behavior, group similar customers, and present main findings.
Data preprocessing and cleaning are done to correct errors, number format correctly,
and replace missing values prior to feeding the data into machine learning algorithms to
cluster and classify.


Process

The project starts with data collection and preprocessing, for example:
Handling missing values by filling them with the column mean.
Encoding categorical data such as Gender with Label Encoding.
Scaling numeric features like Age, Annual Income, and Spending Score.
Upon data cleaning, the Streamlit application (App.py) provides interactive visualizations:
Spending patterns' histograms and scatter plots.
K-Means Clustering is used to segment customers based on similar traits.
Decision Tree Classification for predicting customer segments.
Statistical Hypothesis Testing (T-test) for identifying spending patterns.
Lastly, all the dependencies needed are mentioned in requirements.txt, and the project is published online for immediate access.


Implementation

To deploy the project on Streamlit Cloud, the following was done:
Uploaded project files on GitHub.
Streamlit Community Cloud Opened → Clicked on "New App".
Selected "From GitHub" and referenced the repository. The application was opened with App.py as the main file.
