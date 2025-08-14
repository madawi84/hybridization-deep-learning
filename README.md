# hybridization-deep-learning
A study on deep learning compiler optimization using hybridization in TensorFlow with a benchmarked implementation.

  # ⚡ Acceleration by Hybridization in Deep Learning

This project demonstrates how hybridization — the process of converting imperative code to symbolic computation — accelerates the execution of neural networks in TensorFlow. The approach is benchmarked using `eager` vs `graph` mode with `tf.function`.

## 📘 Concept

Hybridization combines:
- **Imperative programming** (flexibility)  
- **Symbolic graph execution** (optimization & speed)

By converting Python-based models to TensorFlow graphs using `tf.function`, execution becomes faster and memory-efficient.

## 🧠 Key Takeaways

- Implemented a benchmark comparing Eager Mode and Graph Mode
- Used a custom benchmarking class to time 5000 iterations
- Demonstrated significant acceleration using `tf.function`

## 🛠️ Tools Used

- Python
- TensorFlow
- Keras
- Colab

## 🧪 Benchmark Results (Example Output)

| Mode        | Time (seconds) |
|-------------|----------------|
| Eager Mode  | 2.37           |
| Graph Mode  | 1.02           |

> *Graph mode execution significantly outperforms eager mode in this setup.*

## 📂 Project Structure

hybridization-deep-learning/  
│  
├── hybridization_benchmark.ipynb  
├── README.md  
└── requirements.txt  

  
## 📄 Based on

- [Dive into Deep Learning – Hybridization](https://d2l.ai/chapter_computational-performance/hybridize.html#symbolic-programming)
- [TensorFlow tf.function Docs](https://www.tensorflow.org/api_docs/python/tf/function)

## 👩‍💻 Author

Madawi Alsoyohi  
[LinkedIn](https://www.linkedin.com/in/madawi-alsoyohi-7134951a6) | [GitHub](https://github.com/madawi84)
