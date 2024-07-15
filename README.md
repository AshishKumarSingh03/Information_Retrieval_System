# Information Retrieval from Multiple PDF 💁💬 with PaLM2


# How to run?
### STEPS:

Clone the repository

```bash
git clone  https://github.com/AshishKumarSingh03/Information_Retrieval_System.git
```
### STEP 01- Create a new  environment after opening the repository

```bash
python3.8 -m venv genai
```

### STEP 01- Activete Created a new  environment 

```bash
. genai/bin/activate
```


### STEP 03- install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE_API_KEY as follows:

```ini
GOOGLE_API_KEY= "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# Finally run the following command
streamlit run app.py
```

Now,
```bash
open up : http://localhost:8501
```


### Techstack Used:

- Python
- LangChain
- Streamlit 
- PaLM2
- FAISS
