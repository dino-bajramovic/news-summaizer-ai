# news-summaizer-ai

**Tags:** Python · NLP · AI · Text Summarization · News · CSV · JSON · ROUGE · BERTScore

### Overview  
Project for summarizing news articles using natural language processing techniques.  
Based on 200+ articles from Buka.ba, organized by category.

### Project Phases  
**Phase 1 – Data Preparation**  
Extracts structured data (title, date, text, etc.) from raw `.txt` articles into `.csv` and `.json` files.

**Phase 2 – Summarization**  
Generates summaries using:
- Manual extractive & abstractive methods
- AI models: ChatGPT, Gemini, Claude

**Phase 3 – Evaluation**  
Calculates metrics for summary quality:
- Compression, Coverage, Density
- ROUGE-1, ROUGE-2, ROUGE-L
- BERTScore

### Key Features  
- Human and AI-generated summaries  
- Structured output files  
- Automatic evaluation of summarization quality

### Tech Stack  
Python · NLTK · Transformers · scikit-learn · pandas · ROUGE · BERTScore
