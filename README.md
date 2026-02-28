# 🧠 Neural Network From Scratch
### *"I built a brain. With NumPy. No, I will not be taking questions."*

> No TensorFlow. No PyTorch. No hand-holding.  
> Just matrices, math, and a dangerous amount of self-belief.

🔗 **GitHub:** [Prabakaransr19/NeuralNetworkFromScratch](https://github.com/Prabakaransr19/NeuralNetworkFromScratch)

---

## 🤯 What Is This?

This is an **Artificial Neural Network built entirely from scratch** using nothing but **NumPy** and **Pandas**.

That means:
- ❌ No TensorFlow
- ❌ No PyTorch  
- ❌ No Keras
- ❌ No `model.fit()` magic
- ✅ Just raw matrix multiplication, backpropagation, and tears

It classifies **handwritten digits** from the MNIST dataset and achieves **~84% accuracy**.

*84%. On math I wrote myself. From scratch. Let that sink in.*

---

## 🧬 How Does a Neural Network Even Work?

Great question. I also asked this. Many times. Here's the honest summary:

```
Input numbers → Multiply by weights → Add bias → Squish through activation function
→ Get output → Compare to real answer → Calculate how wrong you were → 
Go backwards and fix the weights → Repeat 10,000 times → Profit (maybe)
```

This process is called **backpropagation** and it is either beautiful mathematics or pure suffering, depending on the day.

---

## ✨ Features

- 🔢 **Feedforward Neural Network** — data flows forward, shame flows backward
- 📉 **Backpropagation** — the art of learning from your mistakes, implemented in Python
- ⚡ **Stochastic Gradient Descent** — finds the bottom of the loss function like water finding a drain
- 🖼️ **MNIST Digit Classification** — teaches the computer that 7 is not 1, which is harder than it sounds
- 📊 **~84% Accuracy** — not GPT-4, but built by a human with a laptop and determination
- 🎥 **Demo video included** — because seeing is believing

---

## 🛠️ Tech Stack

*"No ML frameworks were used in the making of this neural network. They were, however, deeply missed."*

| Tool | Role | Vibe |
|---|---|---|
| **Python** | Main language | The GOAT |
| **NumPy** | Matrix operations | Did the heavy lifting while I watched and nodded |
| **Pandas** | Data loading | Read CSVs so I didn't have to think about CSVs |
| **MNIST Dataset** | Training data | 70,000 handwritten digits, infinite patience |
| **Math** | The actual engine | Linear algebra said "hello" and never left |

---

## 📂 Project Structure

```
NeuralNetworkFromScratch/
│
├── neuralnetwork.py   # The brain. 200 lines of pure neural courage.
├── Demo.mp4           # Proof that it works (my most important commit)
└── README.md          # You're here, welcome
```

---

## 🚀 Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/Prabakaransr19/NeuralNetworkFromScratch.git
cd NeuralNetworkFromScratch

# 2. Install the two (2) dependencies
pip install numpy pandas
# That's it. Two packages. Not 847. Two.

# 3. Run the network
python neuralnetwork.py

# 4. Watch the accuracy climb in your terminal and feel like a god
# (results may take a moment — training a brain is not instant)
```

---

## 📊 Accuracy

| Metric | Result |
|---|---|
| Test Accuracy | **~84%** |
| Framework used | **None** |
| Respect earned | **Immeasurable** |
| Times I Googled "what is a derivative" | **Classified** |

84% might not sound like much until you realize:
- This runs on pure NumPy
- Every equation was written by hand
- The network literally learned to read digits
- And you could actually explain every single line of code

That last one? That's the whole point.

---

## 🎓 What I Actually Learned

This project forced me to understand things I'd been skipping over:

- **What weights and biases actually are** — not magic numbers, actual learnable parameters
- **The chain rule** — calculus came back and it had things to say
- **Why activation functions exist** — ReLU said "if negative, you get nothing" and meant it
- **Forward pass vs backward pass** — one is optimistic, one is corrective, both are necessary
- **Why people use TensorFlow** — I understand now. I completely understand.
- **Matrix shapes matter more than anything** — a wrong shape is 30 minutes of debugging minimum

---

## 🎥 Demo

Check out `Demo.mp4` in the repo to see the network training in real time.  
Watch the accuracy go from "embarrassing" to "actually impressive" over several epochs.  
It's genuinely satisfying. Like watching a baby learn to walk, but the baby is math.

---

## 💡 Inspired By

[@sentdex on YouTube](https://youtu.be/w8yWXqWQYmU?si=9glc6zH7wzzrjIS5) — the tutorial that made this feel possible.  
If you want to understand neural networks at a real level (not just `model.fit()`), start there.

---

## 🐛 Known Issues / Honest Notes

- 84% is real, reproducible, and I'm proud of it
- Could be higher with more layers, better hyperparameters, or dark magic
- The code is not optimized — it's educational, which is the point
- If you expected PyTorch-level performance, you have misread the repo name

---

## 📬 Contact

- **GitHub:** [@Prabakaransr19](https://github.com/Prabakaransr19)
- **Portfolio:** [prabakaran-portfolio-two.vercel.app](https://prabakaran-portfolio-two.vercel.app)

---

## 📄 License

MIT — take it, study it, understand it.  
That's the whole philosophy of this project anyway.

---

<p align="center">
  Built with 🧮 NumPy, 📐 calculus I had to relearn, and zero ML frameworks<br><br>
  <i>"Anyone can call model.fit(). Not everyone can write the fit."</i><br><br>
  — Chapter 3 of Prabakaran's dev journey 📖<br>
  <i>(The chapter where things got serious.)</i>
</p>
