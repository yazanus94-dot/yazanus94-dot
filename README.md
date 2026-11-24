<img width="1906" height="1338" alt="image" src="https://github.com/user-attachments/assets/671c0487-b047-410c-8340-0777197155f5" />

# Yazan Aljabari 👋

**Biomedical Signal Processing | Scientific Machine Learning | PhysioNet-Style Benchmarking | AI Evaluation | Software Quality Assurance**

[LinkedIn](https://www.linkedin.com/in/yazan-aljabari-878202139/) · [GitHub](https://github.com/yazanus94-dot)

I build reproducible biomedical signal-processing and ML evaluation projects with an emphasis on
patient-independent validation, scientific correctness and trustworthy evidence. I have **not**
participated in an official PhysioNet Challenge. Synthetic experiments are labelled as such and
are never presented as clinical validation; real-data validation remains pending where licensed
data has not been obtained.

## Featured repositories

### [Physiologically-Modeled-Synthetic-Signals-BME-](https://github.com/yazanus94-dot/Physiologically-Modeled-Synthetic-Signals-BME-)
- **Purpose:** R-peak detection and AAMI ECG arrhythmia classification on synthetic and MIT-BIH data; ECG denoising benchmark.
- **Signals/methods:** ECG; zero-phase SOS band-pass, AAMI mapping, patient-disjoint DS1/DS2 splits, grouped CV.
- **Evidence:** 285 tests pass; CI green. Four scientific-regression tests cover the R-amplitude, record-metadata, annotation-filtering and FP-counting corrections.
- **Status:** ✅ synthetic complete; ⚠️ real MIT-BIH metrics are marked **stale** pending regeneration with licensed data.
- **Docs:** [results status](https://github.com/yazanus94-dot/Physiologically-Modeled-Synthetic-Signals-BME-/blob/main/project-1-ecg-arrhythmia/RESULTS_STATUS.md) · [denoising task](https://github.com/yazanus94-dot/Physiologically-Modeled-Synthetic-Signals-BME-/blob/main/benchmark-tasks/mitbih_nstdb_denoising_benchmark/TASK.md)

### [ecg-physionet-robustness-benchmark](https://github.com/yazanus94-dot/ecg-physionet-robustness-benchmark)
- **Purpose:** Patient-independent ECG arrhythmia classification with noise robustness and two graded benchmark tasks.
- **Signals/methods:** MIT-BIH beats + NSTDB noise, 0.5–40 Hz filtering, 5-fold grouped CV, OOF metrics, fold-local feature selection.
- **Evidence:** 145 core tests + 22 + 23 task tests pass; CI green. Graders independently verify OOF predictions and accept alternative valid methods; adversarial candidates are rejected.
- **Status:** ✅ benchmark tasks and configuration repair complete; ⚠️ model selection, NSTDB noise choice and CIs documented as open scientific decisions.
- **Docs:** [technical report](https://github.com/yazanus94-dot/ecg-physionet-robustness-benchmark/blob/master/reports/TECHNICAL_REPORT.md) · [scientific decisions](https://github.com/yazanus94-dot/ecg-physionet-robustness-benchmark/blob/master/reports/SCIENTIFIC_DECISIONS.md)

### [SleepPSG-CI](https://github.com/yazanus94-dot/SleepPSG-CI)
- **Purpose:** Independent multimodal PSG cognitive-impairment benchmark with authorized-data safeguards.
- **Signals/methods:** EEG/ECG/EOG/EMG/RESP/SpO₂, 30 s epochs, unit-aware features, leave-one-site-out validation, age-conditioned I' metric, patient-cluster bootstrap.
- **Evidence:** 199 tests pass; CI green. Scoreability and cross-site schema fixes plus fold-local missing-column handling verified.
- **Status:** ✅ synthetic benchmark and safeguards complete; ⏳ real EDF validation pending authorized data.
- **Docs:** [benchmark task](https://github.com/yazanus94-dot/SleepPSG-CI/blob/main/benchmark/TASK.md) · [scientific audit](https://github.com/yazanus94-dot/SleepPSG-CI/blob/main/docs/SCIENTIFIC_AUDIT.md)

### [RespiraQA](https://github.com/yazanus94-dot/RespiraQA)
- **Purpose:** Respiratory-sound classification and AI QA with explicit, validated dataset provenance.
- **Signals/methods:** Lung sounds, acoustic features, patient-level grouped splits, imbalance-aware baselines, robustness probes.
- **Evidence:** 69 tests pass; CI green. Synthetic reports carry an explicit `SYNTHETIC DEMO — not clinical validation` provenance banner.
- **Status:** ✅ synthetic end-to-end demo complete; ⏳ real ICBHI validation pending licensed data.
- **Docs:** [methodology](https://github.com/yazanus94-dot/RespiraQA/blob/main/docs/methodology.md) · [real-data workflow (not executed)](https://github.com/yazanus94-dot/RespiraQA/blob/main/docs/REAL_DATA_VALIDATION.md)

## Additional focus

AI evaluation and QA work: [AI-Testing-QA](https://github.com/yazanus94-dot/AI-Testing-QA),
[LLM_Data-Annotation_Projects](https://github.com/yazanus94-dot/LLM_Data-Annotation_Projects),
[RLHF-Preference-Data-QA](https://github.com/yazanus94-dot/RLHF-Preference-Data-QA) and
[QA-Software-Testing-Projects](https://github.com/yazanus94-dot/QA-Software-Testing-Projects).

## Education

- Master's studies in Information Technology — Arizona State University (ASU Online).
- B.Sc. Biomedical Engineering — Jordan University of Science and Technology, 2018.

## Languages

Arabic — Native · English — Professional working proficiency · German — Basic knowledge
