# Abstractive Text Summarization Web-App

Abstractive summarization is the process of generating a summary of a text by understanding its meaning and creating a new text that conveys the same information in a shorter form. Abstractive methods employ more powerful natural language processing techniques to interpret text and generate new summary text, as opposed to selecting the most representative existing excerpts to perform the summarization. 
<a href="#Documentations">Read More</a>

The app is built using "txtai" a powerful NLP library. Txtai builds embeddings databases, which are a union of vector indexes and relational databases. This enables similarity search with SQL. Embeddings databases can stand on their own and/or serve as a powerful knowledge source for large language model (LLM) prompts. 
<a href="#Documentations">Read More</a>

<br>

My Streamlit app allows us to process both raw text and PDF files to get a summary.

## Resources
- <a href="https://summarizze.streamlit.app/">Click for Live Demo</a>
<!-- - <a href="https://www.canva.com/design/DAFiomy01y0/c-0xFFUA2sYer-fgyocu9g/view">Click for Presentation</a>-->
<!-- - <a href="https://docs.google.com/document/d/e/2PACX-1vQTKY3eI-kxC6N_Qj9QNt9AmdMPflHL3Qa8MvX75166BxBEKX-Muz3liu6_z0BBhrGJsl_ysDUY0gm2/pub">Click for Report</a> -->


# Pre-requisites
* [x] Any IDE
* [x] txtai[all] `pip install txtai`
* [x] streamlit `pip install streamlit`
* [x] PyPDF2 `pip install pyPDF2`

# Run the App
- Clone the repository 
- Install the dependencies
- Execute `streamlit run app.py`

# Sample Output
<img src="https://github.com/TheCleverIdiott/summarizer/blob/main/sample_output.png" width="600" height="300">

# Documentations

* <a href="https://neuml.github.io/txtai/">txtai</a>
* <a href="https://docs.streamlit.io/">Streamlit</a>
