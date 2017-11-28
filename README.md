# TopicSummarizer
#### Search Engine to cluster tweets for a topic, visualize the categories within them and summarize each category
Used the twitter streaming api to get tweets for a topic.
When a user searches a topic, extract those tweets and cluster them into sub topics.
Each time a user selects a sub topic, tweets in those sub category is re- clustered.
Apache Solr was used for indexing tweets. This project has a UI/ visualization developed using JavaScript and jQuery. The backend functionalities are implemented as RESTful services.
