<a href="https://claude.ai/artifact/Hza4orUi9ChT762MpRuPvj"><img src="assets/header.svg" width="100%" alt="Krithikk — CS undergrad in Cyber Security at Amrita, Coimbatore. Machine learning, intrusion detection and finance."></a>

<img src="assets/ticker.svg" width="100%" alt="Tools and datasets I work with">

I'm a computer science undergrad specialising in cyber security at Amrita Vishwa Vidyapeetham, Coimbatore. I build software where machine learning meets real systems: catching intrusions on home and IoT networks, and making sense of financial markets.

<img src="assets/sec-ids.svg" width="100%" alt="01 Intrusion Detection">

<img src="assets/ids.svg" width="100%" alt="Animated IDS: IoT devices send traffic through a gateway IDS; a compromised camera triggers an anomaly spike and an alert">

### [Explainable intrusion detection — paper replication](https://github.com/Krithikk18/XAI_Result_replication)
Full replication of *Explainable AI and Random Forest Based Reliable Intrusion Detection System* on CSE-CIC-IDS2018.
- Seven-stage pipeline: preprocessing → Random Forest → secondary classifiers → SHAP (TreeExplainer) → CAM → clean evaluation → HopSkipJump adversarial testing
- 99.96% Random Forest accuracy, with a written account of where results diverged from the paper and why
- Built to fit a 4 GB laptop GPU: stratified sampling, and a scikit-learn fallback when cuML ran out of memory

### IoT intrusion detection research
Lightweight, explainable anomaly detection for smart-home networks.
- Separate models sized for each device class, from microcontroller sensors to the home gateway
- Explainability and adversarial robustness treated as requirements, not extras
- Datasets: N-BaIoT · IoT-23 · UNSW-NB15

<img src="assets/sec-ml.svg" width="100%" alt="02 Machine Learning">

<img src="assets/ml.svg" width="100%" alt="Animated ML panel: neural network forward pass, SHAP attributions, and models sized per device tier">

### [HW-NAS Demo](https://github.com/Krithikk18/HW-NAS_Demo): hardware-aware neural architecture search
A DARTS-style supernet that searches for an intrusion-detection model small enough for the device it runs on.
- Bilevel optimisation: weights learn on training data, architecture learns on validation data plus a hardware penalty (parameters and FLOPs)
- Three device tiers, from microcontroller to gateway, each with its own budget
- Derives a plain PyTorch model from the searched cells, ready to deploy

### [ML Notebooks](https://github.com/Krithikk18/ML_Notebooks)
Machine learning fundamentals, worked through from scratch.

<img src="assets/sec-finance.svg" width="100%" alt="03 Finance">

<img src="assets/finance.svg" width="100%" alt="Animated finance panel: candlesticks with volume and a moving average, and rolling volatility with a forecast">

### [VMarket](https://github.com/Krithikk18/VMarket): volatility forecasting
- GARCH-family models benchmarked against LSTM, with FinBERT news sentiment as an extra signal
- Walk-forward, out-of-sample evaluation with no look-ahead; scored on MSE, MAE and QLIKE with Diebold-Mariano tests
- 🔄 Now extending to Indian large-caps (HDFCBANK, RELIANCE, INFY), rebuilt for full reproducibility

### [Mandate Retry Sequencer](https://github.com/Krithikk18/mandate-retry-sequencer) · Razorpay AI Buildathon
A cost-aware retry policy for failed recurring payments on Indian e-mandates.
- Prices every possible retry date in rupees: expected recovery minus fees, bounce charges and the risk of losing the customer
- Works within NPCI rules: 24-hour pre-debit notice, four attempts per cycle, 00:00–07:00 IST window
- In simulation, lifts recovery from ~32% (fixed schedule) to ~57%; 298 tests passing

### [MarketPulse](https://github.com/Krithikk18/MarketPulse)
A Streamlit app for equity research: LSTM price forecasts alongside FinBERT sentiment.

<img src="assets/sec-stack.svg" width="100%" alt="04 Stack & Learning">

**Languages:** Python · C++ · SQL · TypeScript / JavaScript  
**ML & data:** PyTorch · scikit-learn · SHAP · NumPy · Pandas · statsmodels · arch  
**Web & tools:** React · Supabase · Streamlit · Git · Jupyter · WSL2

**Currently learning:** probability (Harvard Stats 110) · time-series econometrics · data structures & algorithms in C++ · options pricing basics  
**Interests:** Indian macroeconomics · public finance · how markets price risk

<img src="assets/sec-contact.svg" width="100%" alt="05 Reach Me">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/krithikkthilak)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Krithikk18)

> *The difference between playing the stock market and the horses is that one of the horses must win." * — Joey Adams
