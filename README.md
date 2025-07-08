# 🔗 Convolutional Coding and Decoding Simulation (MATLAB)

This MATLAB project simulates **convolutional encoding and decoding** over an **Additive White Gaussian Noise (AWGN)** channel. It compares **hard** and **soft decision Viterbi decoding** methods across various **constraint lengths** and **code rates**, analyzing their impact on **Bit Error Rate (BER)** and **Probability of Decoding Failure**.

> 📊 Ideal for researchers and students interested in error-correcting codes and digital communications.

---

## 🎯 Objectives

- ✅ Understand the principles of convolutional encoding
- ✅ Implement Viterbi decoding (hard & soft decision)
- ✅ Compare BER and decoding failure across parameters
- ✅ Visualize communication performance under noise

---

## 📌 Features

- 🚀 Convolutional encoding using standard generator polynomials  
- 🧠 Hard and soft decision Viterbi decoding  
- 🌪️ AWGN channel simulation  
- 📉 BER vs SNR curve generation  
- ⚠️ Probability of decoding failure analysis  
- 📂 Modular code with clean structure and documentation

---

## 📈 Sample Output

### BER vs Eb/N0 Curve

![BER Plot](results/ber_plot.png)

> *This plot shows the Bit Error Rate (BER) performance for various convolutional coding schemes with different code rates and constraint lengths. Soft decision decoding consistently outperforms hard decision decoding, especially at higher Eb/No values.*

---

## 🧰 Requirements

- MATLAB R2021a or newer
- Communications System Toolbox

---

## 📁 Folder Structure

```
📦convolutional-coding
┣ 📜main.m # Entry point for simulation
┣ 📜encoder.m # Convolutional encoder function
┣ 📜decoder_hard.m # Viterbi decoder (hard decision)
┣ 📜decoder_soft.m # Viterbi decoder (soft decision)
┣ 📜awgn_channel.m # Simulates AWGN noise
┣ 📜plot_results.m # Plots BER 
```
---

## 🧪 How It Works

1. A random bit sequence is generated.
2. The sequence is encoded using a convolutional encoder.
3. The encoded signal is passed through an AWGN channel.
4. The received noisy signal is decoded using:
   - **Hard Decision**: Binary quantized decoding.
   - **Soft Decision**: Uses soft values in path metric computation.
5. BER and probability of decoding failure are calculated across SNR values.
6. Results are visualized using MATLAB plots.

---

## 📚 References

- Proakis, J. G. *Digital Communications*  
- Sklar, B. *Digital Communications: Fundamentals and Applications*  

---

## 👤 Author

Made with ❤️ by **Dhruvil Patel**,  
as part of a group project with **10 team members** from **Dhirubhai Ambani University (DAU)** under guidance of the course instructor Prof. Yash Vasavada.  
Developed for academic and research purposes in the field of digital communications.
