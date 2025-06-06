# 🚀 30-Minute Problem-Solving Challenge

Welcome!  Our incubator is prototyping quick-turnaround health-AI ideas.  
This exercise lets us see how you think, communicate, and leverage modern tools under a tight deadline.

---

## 1. Background (why pneumonia?)

Pneumonia is an infection that inflames the air sacs of the lungs.  
Clinical teams often combine **vital-sign red flags** with **X-ray cues** to decide whether to start treatment quickly.

<details>
<summary>Hints</summary>

* **Vitals that may raise suspicion:**  
  * Abnormal body temperature
  * Abnormal respiratory rate
  * Abnormal white-blood-cell count
</details>

You do **not** need a perfect diagnostic model—just demonstrate a logical approach in the allotted time.

---

## 2. Files provided

| File | Description |
|------|-------------|
| `data/vitals.csv` | 5 rows · columns: `patient_id`, `temp_C`, `resp_rate`, `wbc_count`, `spo2` |
| `data/img_001.png` … `img_005.png` | Matching 256 px chest X-ray thumbnails (`patient_id` embedded in filename) |
| `starter.ipynb` | Empty notebook with data-loading cell to get you moving fast |

An environment variable **`AI_API_KEY`** is already set if you’d like to call a vision-capable LLM API.

---

## 3. Your tasks (30 min total)

| Priority | Task | Minimum expectation |
|----------|------|---------------------|
| **1. Core (required)** | Produce **at least one working method** that outputs for each patient: <br>```<patient_id>, PneumoniaRisk = Yes/No, (optional confidence)``` | Any approach—simple rule, open-source model, or LLM API call—is acceptable. |

---

## 4. Time-box & workflow

1. **Total live time:** 40 minutes  
2. Think aloud or keep a running note so we understand your reasoning.
   
---

## 5. Submission

* Push commits to this repo **or** show your results on screen for the edited `starter.ipynb`.
* Please screen-share at all times.

Good luck—have fun, and show us how you tackle a brand-new problem!
