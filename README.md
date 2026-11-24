<img width="1906" height="1338" alt="image" src="https://github.com/user-attachments/assets/671c0487-b047-410c-8340-0777197155f5" />

# Hi, I'm Yazan 👋

**QA Engineer & AI Trainer** with 8+ years across software engineering and biomedical
engineering. This profile highlights verified work in **biomedical signal processing,
PhysioNet-style research, scientific machine learning and benchmark evaluation**.

> I have **not** participated in an official PhysioNet Challenge. All datasets used are public
> research databases or synthetic fixtures; synthetic experiments are never presented as
> clinical validation.

---

## Featured biomedical signal-processing & ML work

### [Physiologically-Modeled-Synthetic-Signals-BME-](https://github.com/yazanus94-dot/Physiologically-Modeled-Synthetic-Signals-BME-)
**Synthetic and real ECG signal processing, R-peak detection and AAMI arrhythmia classification.**
- **Signals/methods:** ECG (MIT-BIH, synthetic ECGSYN-like), zero-phase SOS band-pass, one-to-one R-peak matching, AAMI mapping, patient-disjoint DS1/DS2 splits, group-fold CV.
- **Verified:** 285 pytest tests pass locally; CI green. Scientific fixes include R-amplitude feature alignment, record metadata units and annotation filtering.
- **Technical report / task:** [project 1 README](https://github.com/yazanus94-dot/Physiologically-Modeled-Synthetic-Signals-BME-/blob/main/project-1-ecg-arrhythmia/README.md) · [denoising benchmark task](https://github.com/yazanus94-dot/Physiologically-Modeled-Synthetic-Signals-BME-/blob/main/benchmark-tasks/mitbih_nstdb_denoising_benchmark/TASK.md)
- **Status:** ✅ complete; ⚠️ committed real-data metric files predate the R-amplitude correction and require regeneration after licensed dataset access.

### [ecg-physionet-robustness-benchmark](https://github.com/yazanus94-dot/ecg-physionet-robustness-benchmark)
**Patient-independent ECG arrhythmia classification with noise-robustness evaluation and graded benchmark tasks.**
- **Signals/methods:** MIT-BIH beats, NSTDB noise, 0.5–40 Hz SOS filtering, 5-fold patient-grouped CV, OOF metrics, SNR sweeps, class-weighted models.
- **Verified:** 143 core tests + 23 benchmark-task tests pass; CI green with grader execution. Fold-local feature selection, incomplete-record handling and documentation corrected.
- **Technical report / tasks:** [technical report](https://github.com/yazanus94-dot/ecg-physionet-robustness-benchmark/blob/master/reports/TECHNICAL_REPORT.md) · [denoising task](https://github.com/yazanus94-dot/ecg-physionet-robustness-benchmark/blob/master/tasks/ecg_denoising_quality/TASK.md) · [arrhythmia task](https://github.com/yazanus94-dot/ecg-physionet-robustness-benchmark/blob/master/tasks/arrhythmia_classification/TASK.md)
- **Status:** ✅ benchmark tasks complete and graded; ⚠️ choice of pure-noise NSTDB records, nested model selection and confidence intervals require an explicit scientific decision.

### [SleepPSG-CI](https://github.com/yazanus94-dot/SleepPSG-CI)
**Independent multimodal PSG cognitive-impairment benchmark with authorized-data safeguards.**
- **Signals/methods:** EEG/ECG/EOG/EMG/RESP/SpO₂, 30 s epochs, unit-aware feature eligibility, leave-one-site-out evaluation, age-conditioned I' metric, patient-cluster bootstrap CIs.
- **Verified:** 196 tests pass; CI green. Scoreability, cross-site schema alignment and filter-padding guards corrected.
- **Report / task:** [benchmark task](https://github.com/yazanus94-dot/SleepPSG-CI/blob/main/benchmark/TASK.md) · [real-data workflow (not executed)](https://github.com/yazanus94-dot/SleepPSG-CI/blob/main/docs/REAL_DATA_VALIDATION.md)
- **Status:** ✅ synthetic benchmark and safeguards complete; ⏳ real EDF validation outstanding (credentials, personal terms acceptance and data access required).

### [RespiraQA](https://github.com/yazanus94-dot/RespiraQA)
**Respiratory-sound classification and AI quality assurance with patient-independent splitting.**
- **Signals/methods:** Lung sounds, librosa acoustic features, patient-level `StratifiedGroupKFold`, imbalance-aware baselines, controlled noise/amplitude/truncation robustness probes.
- **Verified:** 61 tests pass; CI green (install failure fixed by Python 3.12 alignment). Synthetic reports now carry explicit provenance banners.
- **Methodology / workflow:** [methodology](https://github.com/yazanus94-dot/RespiraQA/blob/main/docs/methodology.md) · [real ICBHI workflow (not executed)](https://github.com/yazanus94-dot/RespiraQA/blob/main/docs/REAL_DATA_VALIDATION.md)
- **Status:** ✅ synthetic end-to-end demo complete; ⏳ real ICBHI validation outstanding (licensed dataset must be obtained and terms accepted by me).

---

## What this work demonstrates

- Signal-processing correctness: sampling-rate verification, zero-phase filtering, alignment,
  segmentation boundaries and explicit input validation.
- Evaluation rigor: patient/subject-level splits, fold-local preprocessing, OOF reporting,
  dummy baselines, bootstrap CIs where applicable.
- Reproducibility: fixed seeds, pinned dependencies, deterministic fixtures, documented commands,
  generated expected outputs and automated graders.
- Scientific honesty: synthetic results labelled as synthetic; real-data results reported only
  after legitimate data access; no hidden labels, no fabricated metrics.

## Contact

- 🔭 Working on QA automation, biomedical signal processing and scientific ML evaluation.
- 💬 Ask me about signal processing, test automation, AI evaluation and reproducible benchmarks.
- 🤝 Open to remote and onsite collaboration worldwide.
