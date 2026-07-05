# user_segmentation
My 1st Data Science project using technologies python, pandas, beautiful soup, similarity matrix, cosine similarity.
* Worked with company-provided **IOH DPI** data to analyze user behavior and support user segmentation.
* Utilized an existing **Apache Kafka** streaming pipeline to consume and process real-time data for analytics and downstream processing.
* read the incoming messages from Kafka and process them.
consumer = KafkaConsumer("user-events")

for message in consumer:
    process(message)
