# Evaluation Rubric

Use this rubric when reviewing the intern's submission. Each criterion is scored 1–5.

---

## 1. Works End-to-End (30%)

| Score | Description |
|---|---|
| 5 | Notebook runs top-to-bottom with `Restart & Run All`. Produces a clear final score and sub-scores with no errors. |
| 4 | Runs with minor warnings; output is complete. |
| 3 | Runs but requires small manual fixes (e.g., a hardcoded path). |
| 2 | Partially runs; some cells error out but core logic is present. |
| 1 | Does not run or is mostly incomplete. |

## 2. Technical Depth (25%)

| Score | Description |
|---|---|
| 5 | Implements 3+ dimensions with thoughtful signal processing (e.g., proper filtering, beat detection with onset strength, joint angle math). Handles edge cases like missing keypoints. |
| 4 | Solid implementations of 3 dimensions with reasonable signal processing. |
| 3 | 3 dimensions implemented but approaches are simplistic (e.g., raw variance without smoothing). |
| 2 | Fewer than 3 dimensions or approaches have fundamental flaws. |
| 1 | Minimal technical work; just runs pose estimation without meaningful analysis. |

## 3. Code Quality (20%)

| Score | Description |
|---|---|
| 5 | Clean, modular code. Functions have clear names and single responsibilities. No dead code. Easy to follow without comments. |
| 4 | Well-organized with minor style issues. |
| 3 | Functional but somewhat messy — long cells, unclear variable names, some copy-paste. |
| 2 | Hard to follow; logic is tangled or spread across cells in confusing order. |
| 1 | Unreadable or heavily copy-pasted without understanding. |

## 4. Justification & Write-up (15%)

| Score | Description |
|---|---|
| 5 | Each dimension has a clear rationale. Scoring formula is justified. Limitations and future work are thoughtful and specific. |
| 4 | Good explanations with minor gaps. |
| 3 | Explanations present but surface-level. |
| 2 | Minimal explanations; hard to understand design choices. |
| 1 | No explanations provided. |

## 5. Creativity & Extensions (10%)

| Score | Description |
|---|---|
| 5 | Goes meaningfully beyond requirements — e.g., comparative scoring across videos, audio-visual sync analysis, interactive visualizations, confidence intervals on scores. |
| 4 | One solid extension beyond the minimum. |
| 3 | Meets requirements with minor creative touches. |
| 2 | Meets minimum requirements only. |
| 1 | Below minimum requirements. |

---

## Scoring

```
Final grade = (end_to_end × 0.30) + (technical × 0.25) + (code_quality × 0.20) + (justification × 0.15) + (creativity × 0.10)
```

| Grade | Recommendation |
|---|---|
| 4.0+ | Strong hire — ready to contribute to CV projects |
| 3.0–3.9 | Hire with mentorship — solid foundations, needs guidance |
| 2.0–2.9 | Borderline — discuss in debrief |
| < 2.0 | Pass |

---

## Follow-up Interview Questions

Use these in a 30-minute review call:

1. Walk me through how you chose your quality dimensions. What did you consider and reject?
2. Pick one dimension and explain the math behind your scoring. Why did you normalize it that way?
3. What happens to your pipeline if the dancer is partially occluded for several seconds?
4. How would you extend this to compare two dancers performing the same choreography?
5. If you were scoring this for a dance competition app, what would you change about your approach?
