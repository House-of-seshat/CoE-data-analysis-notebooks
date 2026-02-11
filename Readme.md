**Culture of Elections (CoE) — Data Compilation**

- **Project:** Collection of notebook analyses for the "Culture of Elections" (CoE) study.
- **Location:** Top-level workspace containing pre- and post-election analyses across platforms.

**Overview**

This repository centralizes exploratory analyses and lexicon-based studies related to the Culture of Elections (CoE). It contains Jupyter notebooks analyzing social media data (Twitter, Facebook, TikTok) for both pre-election and post-election periods.

**Folder Structure**

- **Pre-elections/**: Notebooks analyzing data collected before the election.
	- CoE_analysis_Twitter.ipynb — Twitter analysis (pre-elections)
	- CoE_analysis_TikTok.ipynb — TikTok analysis (pre-elections)
	- CoE_analysis_Lexicon_Twitter_Data.ipynb — Lexicon-based analysis on Twitter (pre-elections)
	- CoE_analysis_Facebook.ipynb — Facebook analysis (pre-elections)

- **Post elections/**: Notebooks analyzing data collected after the election.
	- CoE_analysis_Twitter_Post_elections.ipynb — Twitter analysis (post-elections)
	- CoE_analysis_Twitter_MK_analysis.ipynb — Additional Twitter analysis (MK analysis)
	- CoE_analysis_Lexicon_Twitter_Data_post_elections.ipynb — Lexicon-based analysis on Twitter (post-elections)
	- CoE_analysis_Facebook_Post_elections.ipynb — Facebook analysis (post-elections)

**How to use**

- Install Python (3.8+) and Jupyter (JupyterLab or Notebook).
- Create and activate a virtual environment, then install common data-science packages (example):

```bash
python -m venv .venv
.venv\Scripts\activate
pip install --upgrade pip
pip install jupyterlab pandas numpy matplotlib seaborn scikit-learn nltk
```

- Open the workspace folder in your editor or launch JupyterLab:

```bash
jupyter lab
```

- Open any notebook in the `Pre-elections/` or `Post elections/` folders and run cells sequentially.

**Data Sources**

- The data used in these analyses can be accessed via Hugging Face Datasets: https://huggingface.co/the-house-of-seshat