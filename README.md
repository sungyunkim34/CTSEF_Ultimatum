# CTSEF_Ultimatum
# Ultimatum Game Experiment (Science Fair Project)

This repository contains an online implementation of the **Ultimatum Game** using [jsPsych](https://www.jspsych.org/).  
It was developed by **Sungyun Kim (Hotchkiss School)** as part of the Science Fair project:

> **Analyzing Fairness Learning Dynamics in the Ultimatum Game via Softmax-Policy Q-Learning Model**

---

## 📖 Overview
The experiment consists of two parts:

1. **Pre-survey**
   - Demographics (age, gender, monthly allowance/income)
   - Subjective economic affluence (2 questions)
   - Personality (TIPI short, 5 items)

2. **Ultimatum Game Trials**
   - Total stake: `$100`, `$500`, or `$2,000`
   - Division ratios: `50:50`, `33:67`, `25:75`
   - Relationship conditions: `friend`, `stranger`, `enemy`
   - 27 possible combinations in total  
   - Each participant is shown **10 randomized trials**

At the end of the experiment, data can be saved as a `.csv` file containing participant responses and reaction times.

---

## 🚀 How to Run
1. Clone or download this repository.
2. Open `index.html` in a web browser (Google Chrome recommended).
3. The experiment will start automatically.
4. At the end, click **Finish** to view and download results.

---

## 🌐 Online Deployment (GitHub Pages)
To deploy this experiment online:

1. Create a public repository on GitHub and upload this code.  
2. Go to **Settings → Pages**.  
3. Select `main` branch and `/ (root)` folder.  
4. A link like `https://username.github.io/ultimatum-experiment/` will be generated.  
5. Share this link with participants.

---

## 📊 Data Collected
Each trial logs:
- `trial_id`
- `total_amount`
- `ratio`
- `self_amt` (amount offered to participant)
- `other_amt` (amount offered to proposer)
- `relation`
- `choice` (0 = Reject, 1 = Accept)
- `rt` (reaction time in ms)

---

## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements
- Developed using [jsPsych](https://www.jspsych.org/).
- Thanks to participants who contribute data for this Science Fair project.

