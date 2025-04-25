
# Big Data Transaction Default Detection

This project is part of a university assignment for Big Data Processing. It simulates a bank’s infrastructure for detecting default transactions in real time using Apache Kafka and Apache Spark Streaming.

## 📁 Project Structure

- `A2A.ipynb`: Initial data exploration and understanding
- `A2B_Task1_producer.ipynb`: Kafka Producer — sends simulated transactions to the Kafka topic
- `A2B_Task2_spark_streaming.ipynb`: Spark Streaming — processes incoming transactions in real time
- `A2B_Task3_consumer.ipynb`: Kafka Consumer — receives and logs detected default transactions

## ⚙️ Technologies Used

- Apache Kafka
- Apache Spark (PySpark)
- Jupyter Notebooks
- Python

## 🧠 How It Works

1. **Producer** generates and sends transactions.
2. **Spark Streaming** ingests the transactions and applies detection rules.
3. **Consumer** receives any transactions flagged as defaults for logging or further action.

## 📦 Setup Instructions

1. Start Zookeeper and Kafka Server.
2. Create Kafka topics (e.g., `transactions`, `defaults`).
3. Run each notebook in order:
   - `A2B_Task1_producer.ipynb`
   - `A2B_Task2_spark_streaming.ipynb`
   - `A2B_Task3_consumer.ipynb`

## 📌 Notes

- Make sure your local Kafka setup is running properly.
- Update topic names and broker addresses if needed in the code.

## 👩‍💻 Author

GitHub: [xc017](https://github.com/xc017)
