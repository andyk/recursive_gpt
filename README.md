Recursion implemented using English as the programming language and GPT as the runtime.

To run:

    pip install openai
    OPENAI_API_KEY=YOUR_KEY_HERE python run_recursive_gpt.py < prompt_fibonnaci.txt

Examples of recursive prompts are in prompt_* files.


To run without python (more manual process):

1. open OpenAI Playground
2. Paste the prompt into the model (text-davinci-003", temperature=0, max_tokens=2048)
3. Click Submit. That should generate a new prompt.
4. Keep running each successive prompt till the base case is hit.