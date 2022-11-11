# Generate moral societal norms - HW6

## Backstory

Pied Piper is a company that tries to create AI-general intelligence. In order to build Artificial general intelligence, AI needs help from another AI that guides AGI on moral values. In today’s world AI lacks consciousness, moral decision-making, and understanding of societal norms. We are here to help AI understand moral and societal conduct in different scenarios that are commonly employed by humans.

Your job is to assist Mr. Richard in one of our new use-case projects regarding text generation through AI. Here we focus on our model ’s ability to generate text based on logical reasoning used in everyday situations and make decisions (moral or immoral) as humans would. You need to plug the relevant GPT-2 code from huggingface, plot curves and achieve the best results based on fine tuning hyperparameters and inference parameters. Based on your results, Mr. Gregor will investigate the feasibility and scope of the project. Thereby, deciding whether to move forward with it or not. 

## Description

The dataset used for HW6 is “moral_stories” from hugging face [https://huggingface.co/datasets/demelin/moral_stories]. We are using the GPT-2 model to generate moral social conduct (norm column of the dataset). We will be using GPT2 for this task. This HW aims to achieve the following-
* The ability to use and navigate the hugging face website and GitHub repositories to use relevant code.
* Ability to use and integrate wandb as a logger and use plot curves.
* A better understanding of Neural networks and the effect of hyperparameter changes on the model.

## What you need to do: 

***

![alt text](https://github.com/vikramNU/introaihw6/blob/main/images/HW6.png)

* You need to go to the hugging face website and within the transformers section (refer the link - [https://huggingface.co/docs/transformers/v4.21.2/en/index] go through the modules of hugging face API and GPT2 to understand how to implement functions like GPT2Tokenizer, GPT2LMHeadModel, Training arguments, Trainer in the main code python notebook shared for the HW in the respective places.

* Next, you need to fine-tune the GPT2 model by experimenting with training hyperparameters like training_epoch (within the range of 1 to 5), batch_size (for evaluation and training), learning rate and weight decay and inference hyperparameters like top_p, top_k and temperature when generating the model and finally choose the best fit value for your model.

* Finally, you need to plot the loss curves using wandb (refer to documentation- [https://docs.wandb.ai/guides/integrations/huggingface] ) to track your losses.

* Get the tokens and predicted tokens for a sample data of your own choice (for example- “Parents are allowed to decide”). 

* Decode those tokens and write an evaluation code to get the generated text for the test data. 

* Finally, evaluate your model results using the BLEU score.

## What is expected : 

***
* You need to complete the code blocks in all relevant places.
* Add graphs for at least 3 tuning changes for GPT2 hyperparameters and the loss curves from wandb and explain your reasoning regarding the changes in result for each hyperparameter change.
* Explain the effect of changing the inference hyperparameters.
* Report your BLEU score for each scenario in a tabular format.

Marks:
Graphs - 3
BLEU Score table - 3
Code - 4
