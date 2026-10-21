## Rohan Sinha

Applied AI and systems engineer. Final-year IT at MIT Manipal (graduating May 2027).
Based in Abu Dhabi with a UAE residence visa (no sponsorship required). Looking for
applied AI engineering roles in the UAE.


---

### Experience

**Software Engineer Intern — Sarus Inc.** · June 2026 – September 2026

Sole engineer on **Splendid Sudoku** and **Splendid Killer Sudoku**, two cross-platform
Flutter apps shipped to the App Store and Google Play. Built both puzzle engines from
scratch as standalone Dart packages: a technique-based difficulty grader for classic
Sudoku, and a cage-aware Killer Sudoku solver with CP-SAT uniqueness validation and a
pre-generated puzzle pool. Shipped Firebase auth and account deletion, offline-first
resumable game state, AdMob with consent compliance (UMP/ATT), and Analytics/Crashlytics,
and took both apps through store review to approval.

---

### Selected work

**On-Device Acoustic Event Detection** — Deep learning mini project comparing CNN,
MobileNetV3-Small, CRNN and an Audio Spectrogram Transformer on UrbanSound8K under the
accuracy–efficiency trade-off. Ten-fold evaluation with a shared preprocessing pipeline,
PyTorch and ONNX Runtime int8 quantization, pruning, and CPU latency benchmarking. AST
reached 85.9% accuracy; ImageNet-pretrained MobileNetV3-S reached 78.9% at a fraction of
the size. Found that MACs don't predict CPU latency and that pruning gave no CPU speedup.

**Credit Risk Prediction** — Explainable ensemble framework for credit default prediction,
focused on decision-threshold selection under class imbalance. First-authored paper
accepted and presented at IEEE INDISCON 2026. Extending it into an IEEE Access journal
paper: leak-free pipeline, 28 pre-registered hypotheses, calibration theory, external
validation on German Credit and Taiwan Default, SHAP explainability, and a calibrated
Flask deployment. Code and results are public and reproducible.

**Pipecat Voice Agent** — Real-time conversational voice agent, sub-800ms end-to-end.
FastWhisper ASR → Llama 3.2 via Ollama → Kokoro ONNX TTS, with Silero VAD and LiveKit
WebRTC transport, self-hosted on an RTX 3090. Moving TTS to CUDA ONNX Runtime took
synthesis from ~15s to ~200ms.

---

### Working with

Python · PyTorch · ONNX Runtime · CUDA · scikit-learn · SHAP · Dart / Flutter · Firebase ·
OR-Tools (CP-SAT) · FastAPI · Flask

---

📍 Abu Dhabi, UAE · [LinkedIn](https://www.linkedin.com/in/rohan-sinha-b868b8403) · 1.rohanrsinha@gmail.com
