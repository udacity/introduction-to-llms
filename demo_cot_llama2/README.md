# Purpose of This Directory
This directory allows you to recreate and experiment upon the "chain of thought and tiggering" demo.
 
## Folder Structure
```
exercises
    |_ demo_cot_llama2
    |   |_ demo_cot_and_triggers.ipynb
    |_ README.md
```

## Gotchas
Please make sure you add your `TOGETHER_API_KEY` to your `env`, or paste it in directly into the notebook, e.g.:
`TOGETHER_API_KEY = "YOUR_KEY_HERE"``

If running `query_model(user_prompt)`, returns the error: `KeyError: 'output'`, then your `TOGETHER_API_KEY` has not been correctly added.
