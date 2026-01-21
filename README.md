## Emotion-Constrained Screenplay Generator From Text
This project combines a emotion-tagging model from hugging face: [bhadresh-savani/distilbert-base-uncased-emotion](https://huggingface.co/bhadresh-savani/distilbert-base-uncased-emotion) with OpenAI's [gpt-4o-mini](https://platform.openai.com/docs/models/gpt-4o-mini) (accessed via API key)

### Overview
The jupyter notebook contained in this repository serves as a proof-of-concept for a screenplay generating system capable of expressing emotion accurately via subtext. This is accomplished by using outputted emotion tags per sentence as an additional instruction when prompting the generative model, theoretically improving implicit emotional expression.

### Requirements
- Python 3+
- NLTK
- OpenAI
- os

### How to Run
1. Clone repository and open the jupyter notebook
2. Navigate to the repository in your terminal and run the following code (replace "YOURKEY" with the API key contained in key.txt):
#### Anaconda Prompt / Command Prompt
```
set OPENAI_API_KEY=YOURKEY
```
#### PowerShell
```
$env:OPENAI_API_KEY="YOURKEY"
```
3. Run cells in order

