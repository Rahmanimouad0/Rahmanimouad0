### Mouad Rahmani

Computer Science & Engineering student at UESTC, China — focused on AI, cybersecurity, and systems.

I build things that combine transparent detection logic with machine learning and, increasingly, AI agents — with an emphasis on evidence, testing, and honest scope over polish.

---

#### Featured projects

**[SentinelAI](https://github.com/Rahmanimouad0/sentinelai)** — Local-first defensive network detection and investigation platform. FastAPI backend with SQLAlchemy/Alembic, a transparent port-scan detection rule, evidence-backed alerting, and a candidate MITRE ATT&CK (T1046) mapping drawn from a local versioned catalog. Fully tested (unit + API), linted, type-checked, and wired to CI.
`Python · FastAPI · SQLAlchemy · Alembic · pytest · GitHub Actions`

**[FLUTE Broadcast Platform](https://github.com/Rahmanimouad0/flute-broadcast-platform)** — An RFC 6726–compliant file distribution system for low-bandwidth, one-way broadcast scenarios, wrapping a real FLUTE implementation with a control panel and application-layer security. Includes a custom Rust receiver, AES-256-GCM/RSA-OAEP encryption, and 32 tests covering persistence, encryption, and adversarial cases (tamper detection, wrong-key rejection, race conditions).
`Rust · Python · Flask · UDP Multicast · AES-256-GCM · RSA-OAEP`

**[PhishLens](https://github.com/Rahmanimouad0/phishlens)** — *In progress.* An LLM agent that autonomously selects and calls specialized tools (URL analysis, an XGBoost classifier, DNS/HTML checks) to investigate phishing URLs, built around the question of whether tool-using agents actually outperform an ML-only or LLM-only baseline. Evaluation harness (four-way comparison) in progress.
`Python · Qwen3 (Ollama) · XGBoost · Streamlit · SQLite`

**[Phishing URL Detector](https://github.com/Rahmanimouad0/phishing-url-detector)** — ML phishing classifier trained on URL and HTML features (Logistic Regression, Random Forest, XGBoost, DistilBERT), explained with SHAP, and shipped as a Flask API with a Chrome extension. Documents a real deployment failure — a dataset-construction bias that caused nearly all legitimate sites to be flagged — traced and fixed using SHAP.
`Python · XGBoost · DistilBERT · SHAP · Flask · Chrome Extension`

---

#### Technologies

Python · Rust · FastAPI · Flask · SQLAlchemy · XGBoost · SHAP · AI agents / tool-use LLMs · Docker · GitHub Actions

---

📫 tradeconnectmrh@gmail.com
