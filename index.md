Peter Shamoun, pshamoun@ucsd.edu
Section A10, Alex Warstadt

**What is the most interesting topic covered in your domain this quarter?**
The most interesting topic covered in my domain so far has been the different dataset techniques used to get better results from small language models. These are interesting to me becuase they go beyoung classical hyperparameter or model structure improvements. For example, curriculum learning and training models on phonemes are creative ways to teach models the same information in different ways. 

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
I would like to pursue how small language models can be trained to perform tool calling and other lightweight agentic behaviors despite their limited parameter budgets. This is interesting to me because tool use represents a way to extend a model’s effective capabilities without expanding the core architecture. The investigation would focus on designing a minimal set of tool APIs and then training the BabyLM models to identify when a tool is needed, construct the correct call, and integrate the returned result into a final answer. 

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
Right now, our current quarter 1 project has revolved around recreating past submissions to the BabyLM challenge and running hyperparameter sweeps. One change I would make is having the project be about our creation of a new technique that we can submit for the BabyLM challenge.

**What other techniques would you be interested in using in your project?**
I would also be interested in trying retrieval-augmented training, where the model learns to look up information from a small database before answering. This would pair well with tool calling, since both approaches give the model ways to rely on external resources instead of trying to store everything in its parameters. Another technique I’d like to explore is using short, structured reasoning steps, very small “plans” the model writes before answering, to see if they help BabyLM models stay organized on harder tasks without needing full chain-of-thought