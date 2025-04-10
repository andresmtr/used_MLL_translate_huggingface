🧠 Offline Multilingual Translation using Hugging Face LLMs

This project explores the use of large language models (LLMs) for multilingual translation entirely offline, leveraging open-source models from Hugging Face. The main goal is to ensure data privacy by performing all translation tasks locally, without sending any information to external servers or over the internet.

📌 Features

✅ Offline multilingual translation using pre-trained Hugging Face models.
✅ Support for multiple languages using MarianMT and other translation models.
✅ Maintains full data privacy.
✅ Tested on both CPU and GPU environments.
✅ Example scripts and datasets included for easy testing.

🛠️ Installation

Clone the repository:

git clone https://github.com/andresmtr/used_MLL_translate_huggingface.git
cd used_MLL_translate_huggingface

📁 Files

test_models_translate.ipynb: Jupyter Notebook demonstrating how to use translation models.
Textos.csv: Example text data in different languages.
base_trans.xlsx: Translations saved in spreadsheet format.
downloadModelF.png, used_gpu.png: Visual guides showing how models are downloaded and GPU usage.
.gitignore: Specifies files to exclude from version control.

🧪 How to Use

Open the test_models_translate.ipynb notebook.
Load your input data (e.g. Textos.csv).
Choose the appropriate translation model.
Run the translation cells.
Save the results locally (e.g. in base_trans.xlsx).

🔐 Why Offline?

Performing translations offline ensures:

✅ No data is sent online.
✅ Increased security for confidential or sensitive information.
✅ Faster translation for large batches without server delays.
