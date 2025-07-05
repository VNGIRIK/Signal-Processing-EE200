#  Frequency Mixer and Demixer using Signal Processing
Course Project – EE200 (Signals and Systems)
Feb 2025 – Apr 2025

📌 Objective
To simulate frequency mixing (modulation) and demixing (demodulation) operations in Python, demonstrating the core principles of signal translation in the time and frequency domain.

⚙️ Approach
🧮 Frequency Mixing: Simulated multiplication of a baseband input signal with a high-frequency carrier wave to shift the signal in the frequency spectrum.

🔄 Frequency Demixing: Applied coherent detection by multiplying the mixed signal with the same carrier, followed by low-pass filtering to recover the original baseband signal.

📊 Visualization:

Time-domain and frequency-domain representations plotted using matplotlib.

Used FFT to analyze spectrum shifts before and after mixing.

🐍 Technologies: Python, NumPy, SciPy, Matplotlib

✅ Result
Successfully demonstrated mixing and demixing processes using synthetic signals.

Validated signal recovery with minimal distortion through accurate carrier synchronization and filtering.

Gained a better understanding of real-world applications such as AM radio transmission, signal modulation, and demodulation techniques.

📁 Repository Structure
bash
Copy code
├── mixer.py              # Frequency mixing code
├── demixer.py            # Frequency demixing code
├── utils.py              # Helper functions (e.g., filters, plots)
├── signals/              # Sample input signals
├── plots/                # Generated plots
└── README.md             # Project documentation

🧠 Learnings
Understood the mathematical basis of mixing (convolution in frequency domain).

Applied FIR/IIR filters practically to isolate desired signals.

Practiced the use of FFT and signal analysis tools in Python.

🔗 License
This project is for academic demonstration purposes. Feel free to fork or reference for learning.
