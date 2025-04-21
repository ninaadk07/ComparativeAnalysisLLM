# Comparative Analysis LLM
This project evaluates the financial reasoning capabilities of Large Language Models (LLMs) — Claude, GPT-4o, and Gemini — across three key tasks: financial sentiment analysis, stock price forecasting, and personalized investment strategy generation. It includes experiment code, synthetic client generation, reinforcement learning loops, and performance evaluation using metrics like RMSE, MAPE, ROUGE, and Sharpe Ratio. The repository is organized by experiment, with data files, model outputs, and analysis scripts. This work contributes to AI-driven financial research and demonstrates the strengths and limitations of general-purpose LLMs in complex financial decision-making. Ideal for researchers in NLP, fintech, and algorithmic finance.
The structure of this GitHub repository is as follows:
-> Experiment1Final.ipynb ,Experiment2Final.ipynb, and Experiment3Final.ipynb consist of the finalized Jupyter notebook files for each experiment, with large datasets (2011-2021 for training and 2022 onwards for evaluation)
-> Experiment1.ipynb, Experiment2.ipynb, and Experiment3.ipynb contain the same Jupyter notebook files with small datasets for both training and evaluation that are quick and efficient to run, however with significantly less accurate results.

None of these files will run as currently provided as they rely on a secret API key for each LLM - if wish to run, please email me (zcabkul@ucl.ac.uk) for these API keys.
Then, please replace the empty values for the following variables with their respective API key:
-> CLAUDE_API_KEY
-> GPT_API_KEY
-> GEMINI_API_KEY 
and the code will be able to run thereafter
