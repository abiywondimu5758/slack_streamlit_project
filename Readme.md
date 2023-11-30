# Slack Analytics Dashboard

This Streamlit-based dashboard provides insights into Slack data, including user activities, message distribution, word clouds, and more. It incorporates elements of Exploratory Data Analysis (EDA) and integrates topic modeling results and sentiment analysis.

## How to Use

1. **Installation:** Ensure you have the required libraries by running:
    ```bash
    pip install streamlit pandas matplotlib seaborn wordcloud gensim
    ```

2. **Clone Repository:**
    ```bash
    git clone https://github.com/your-username/slack-analytics-dashboard.git
    cd slack-analytics-dashboard
    ```

3. **Run the Dashboard:**
    ```bash
    streamlit run dashboard.py
    ```

4. **Navigate the Dashboard:**
    - Use the sidebar to select different charts.
    - Explore insights related to top users, message distribution, word clouds, and more.

## Features

### Charts Available
1. **Top Users:** Bar chart displaying the top users.
2. **Message Distribution:** Countplot showing the distribution of messages across hours.
3. **Word Cloud:** Visual representation of word clouds for messages.
4. **User Reply Counts:** Bar chart depicting user reply counts.
5. **Top Message Senders:** Bar chart highlighting the top message senders.
6. **Average Reply Count per User:** Bar chart showcasing the average reply count per user.
7. **Average Reply Users Count per User:** Bar chart displaying the average reply users count per user.
8. **Average Word Count per Message:** Histogram presenting the average word count per message.
9. **WordCloud for Each Channel:** Word clouds for messages in each channel.
10. **User Reactions:** Bar chart indicating user reactions.

### Additional Insights
- **Message Classification Distribution:** Countplot showing the distribution of message categories.
- **Topic Modeling Results:** Displaying results from the Topic Modeling model.
- **Sentiment Analysis:** Plot depicting sentiment over time.

### MLflow Integration
- Model information from MLflow is presented, including the number of topics.

### Download Data
- A link is provided to download the Slack data used in the analysis.

## Contribution

Feel free to contribute to the development of this Slack Analytics Dashboard. You can report issues, suggest improvements, or add new features. Create a pull request with your changes, and let's make this dashboard more insightful together!
