# LangGraph Tutorials (Gemini)

This repo contains my personal follow-along notebooks from a LangGraph YouTube course, adapted to use the Google Gemini API via `langchain-google-genai` instead of OpenAI.

## What is different from the course
- Uses `ChatGoogleGenerativeAI` with `gemini-2.5-flash`.
- Loads credentials from a local `.env` file (not committed).

## Setup
1. Create and activate a virtual environment.
2. Install dependencies:

```
pip install -r requirements.txt
```

3. Create a `.env` file in the project root:

```
GOOGLE_API_KEY=your_key_here
```

## Notebooks
- `0_test_installation.ipynb`
- `1_bmi_workflow.ipynb`
- `2_simple_llm_workflow.ipynb`
- `3_prompt_chaining.ipynb`
- `4_batsaman_workflow.ipynb`
- `5_CSS_essay_workflow.ipynb`

## Notes
- Do not commit `.env` or API keys.
- If you want to run Gemini notebooks, make sure your key is set and valid.
