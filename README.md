# Streaming-05-smart-smoker

- Author: Shanti Kandel
- Date: September 22, 2023
  
This project serves as a data generator designed to facilitate the streaming of sensor data originating from a smart smoker system. The data, which encompasses temperature measurements for the smoker apparatus along with two distinct food items (referred to as Food A and Food B), is initially stored in a CSV file. The data producer's primary function is to extract this information from the CSV file and subsequently transmit it to designated RabbitMQ queues. It's important to note that these temperature readings are captured at 30-second intervals.

In essence, this project acts as a conduit for relaying sensor data collected from a smart smoker system. This data is originally recorded in a CSV file and is composed of temperature data pertaining to the smoker itself and two different food items, each having its unique identity as Food A and Food B. These temperature readings are systematically acquired every half-minute and are then processed by the data producer, which dispatches them to RabbitMQ queues for further utilization.

# Prerequisites

|1.Git|
|2.Python 3.7+ (3.11+ preferred)|
|3.VS Code Editor|
|4.VS Code Extension: Python (by Microsoft)|

# Module imported
- pika
-  sys
- webbrowser
- csv
- time
- logging
  
# RabbitMQ Console and Terminal Screenshots
<img width="1671" alt="smoker_producer" src="https://github.com/Shantik998/Streaming-05-smart-smoker/assets/84759571/318c8263-35ba-47be-bd4c-f2663978f435">
<img width="1524" alt="smoker_consumer" src="https://github.com/Shantik998/Streaming-05-smart-smoker/assets/84759571/7342c941-7728-465e-8c32-aa8f31a5935c">
<img width="1645" alt="Screenshot 2023-09-22 at 11 52 48 PM" src="https://github.com/Shantik998/Streaming-05-smart-smoker/assets/84759571/e2108602-17c3-4d8b-b41c-ee08e8b67edd">
