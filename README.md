# text-summarization-engine
Task engine for summarizing text using LLaMA 3

## Hugging Face Token Setup
 
To use the `meta-llama/Meta-Llama-3-8B-Instruct` model, you need a Hugging Face token.

1. **Get Your Token**:
   - Log in to [Hugging Face](https://huggingface.co), go to Settings > Access Tokens, and generate a token.

2. **Option 1: Store Locally**:
   - Run this command and enter your token when prompted:
     ```bash
     huggingface-cli login
     ```

3. **Option 2: Use an Environment Variable**:
   - Set the `HF_TOKEN` variable before running the script:
     ```bash
     export HF_TOKEN=your_token_here
     python summarization.py
     ```
   - On Windows (Command Prompt):
     ```cmd
     set HF_TOKEN=your_token_here
     python summarization.py
     ```

**Note**: Do not include your token in this repository. It’s private and should be managed locally or via environment variables.
