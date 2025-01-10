
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NyaySearch - Legal Document Search</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>NyaySearch</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Support us</a></li>
                <li><a href="#">About us</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-text">
            <h2>Search for Legal Documents, Case Laws and more</h2>
            <div class="search-bar">
                <input type="text" placeholder="Search legal cases, statutes, and precedents">
                <button><img src="search-icon.png" alt="Search"></button>
            </div>
            <section class="quick-search">
                <h3>Quick Search :</h3>
                <div class="search-options">
                    <button>Case Laws</button>
                    <button>Judgements</button>
                    <button>Court Orders</button>
                    <button>Legal Articles</button>
                </div>
            </section>
        </div>
    </section>



    <footer>
        <p>&copy; 2024 NyaySearch. All rights reserved.</p>
    </footer>
</body>
</html>
## About The Project
LawGPT is a RAG based generative AI attorney chatbot that is trained using Indian Penal Code data. This project was developed using Streamlit LangChain and TogetherAI API for the LLM. Ask any questions to the attorney and it will give you the right justice as per the IPC. Are you a noob in knowing your rights? then this is for you!
<br>

<div align=



### Check out the live demo on Hugging Face <a href="https://huggingface.co/spaces/harshitv804/NYAY SEARCH"><img src="https://static.vecteezy.com/system/resources/previews/009/384/880/non_2x/click-here-button-clipart-design-illustration-free-png.png" width="120" height="auto"></a>

## Getting Started

#### 1. Clone the repository:
   - ```
     git clone https://github.com/harshitv804/LawGPT.git
     ```
#### 2. Install necessary packages:
   - ```
     pip install -r requirements.txt
     ```
#### 3. Run the `ingest.py` file, preferably on kaggle or colab for faster embeddings processing and then download the `ipc_vector_db` from the output folder and save it locally.
#### 4. Sign up with Together AI today and get $25 worth of free credit! 🎉 Whether you choose to use it for a short-term project or opt for a long-term commitment, Together AI offers cost-effective solutions compared to the OpenAI API. 🚀 You also have the flexibility to explore other Language Models (LLMs) or APIs if you prefer. For a comprehensive list of options, check out this link: [python.langchain.com/docs/integrations/llms](https://python.langchain.com/docs/integrations/llms) . Once signed up, seamlessly integrate Together AI into your Python environment by setting the API Key as an environment variable. 💻✨ 
   - ```
      os.environ["TOGETHER_API_KEY"] = "YOUR_TOGETHER_API_KEY"`
     ```
   - If you are going to host it in streamlit, huggingface or other...
      - Save it in the secrets variable provided by the hosting with the name `TOGETHER_API_KEY` and key as `YOUR_TOGETHER_API_KEY`.

#### 5. To run the `app.py` file, open the CMD Terminal and and type `streamlit run FULL_FILE_PATH_OF_APP.PY`.

## Contact
If you have any questions or feedback, please raise an [github issue](https://github.com/harshitv804/LawGPT/issues).
