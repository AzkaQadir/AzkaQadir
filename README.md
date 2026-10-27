# Hi, I'm Azka 👋

**MS Artificial Intelligence @ NUST Islamabad**

I work on evaluating vision-language models: building benchmarks and metrics that show when a model's answer isn't grounded in what the image actually shows. I get unreasonably attached to making things actually work.

## Research

**[Medical VLM Evidence Reliance](https://github.com/AzkaQadir/evidence-reliance-medical-vlm)** 
Measures whether medical VLMs rely on real image evidence on chest X-rays, using a time-matched control and patient-clustered bootstrap CIs. Accuracy and reliance can diverge: in a DenseNet fine-tuned with a planted shortcut, AUC rose from 0.82 to 1.00 while reliance on the true evidence fell from 0.076 to 0.000.
`MedGemma` `Qwen2.5-VL` `ChestX-ray14` `Bootstrap`

**[What Breaks Next](https://apartresearch.com/sprints/projects/what-breaks-next-4aza)** (Apart Research sprint, early-stage)
A failure taxonomy and sixteen one-day verification checks for agentic AI evaluations.

**[Multimodal Fallacy Detection](https://github.com/AzkaQadir/multimodal-fallacy-detection)**
WavLM (audio) + RoBERTa (text) to detect and classify fallacies in political speech. F1 0.90 on binary detection, 0.65 on six classes. Detecting a claim unsupported by its evidence is the same problem as detecting a model output not grounded in its source.
`PyTorch` `WavLM` `RoBERTa` `Multimodal`

**[BioASQ 14b: Biomedical QA](https://github.com/AzkaQadir/bioasq14b-phaseB)**
4-bit Mistral-7B with TF-IDF retrieval and few-shot prompting on a single T4, no fine-tuning. Yes/no macro-F1 0.9549 against a batch majority of 0.9377. ROUGE-2 and ROUGE-SU4 implemented from scratch, with ablations.
`Mistral-7B` `Quantization` `Evaluation`

## Other projects

**[MeetMind](https://github.com/AzkaQadir/MeetMind)** — AI meeting intelligence
Whisper + Pyannote + distilRoBERTa + LangChain + ChromaDB turn a meeting recording into transcripts, speaker-level emotion analysis, action items and a RAG-powered Q&A chatbot. Runs locally via Ollama or in the cloud via OpenAI. Dockerized, deployed on HuggingFace Spaces.
`Python` `LangChain` `RAG` `Whisper` `Docker`

**BDD100K Object Detection Benchmark**
Benchmarked five YOLO variants (v8n to v11x) with training configs held constant. Best model: mAP@0.5 0.58, precision 0.75.
`YOLO` `PyTorch` `Ultralytics`

## Experience

- Research Intern (Remote), AgenticOCC Occupancy Forecasting Project, Oct 2026 – present
- Research Collaborator, autism detection from children's speech
- Research Intern, The Neuron Gorge, Jun – Aug 2025
- AI Intern, SPS (IBM Watsonx)

## Stack

```
Languages     Python · SQL
ML/DL         PyTorch · TensorFlow · Scikit-learn · HuggingFace
LLMs & RAG    LangChain · ChromaDB · Ollama · OpenAI/Claude/Gemini APIs · Flan-T5 · Whisper
Evaluation    Custom metrics · ablations · Cohen's κ · bootstrap CI · McNemar · DeLong · Holm
CV            OpenCV · YOLO · Grad-CAM
Deployment    Docker · Gradio · HuggingFace Spaces · Streamlit
Tools         Git · LaTeX · Label Studio · Weights & Biases
```

## Certifications
AWS AI & ML Scholars (Udacity, 2026) · AWS AI Practitioner Challenge (Udacity, 2026)

[LinkedIn](https://linkedin.com/in/azka-qadir-b8a0a020b)
