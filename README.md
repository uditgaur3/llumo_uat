# llumo_uat


# RAGAs Evaluation without OpenAI

This project computes RAG-style metrics **without using OpenAI API** by using Hugging Face's `sentence-transformers`.

## Metrics Calculated:
- Faithfulness = cosine similarity between system context and assistant response
- Answer Relevancy = cosine similarity between user query and assistant response

## Model Used
- `all-MiniLM-L6-v2` from Hugging Face

## Output
- `raga_output.json` contains the computed scores

## Note
- No external API (like OpenAI) was used. All computation was done locally using pre-trained open-source models.