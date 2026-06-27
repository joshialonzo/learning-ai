# Essentials of Prompt Engineering

## Introduction

Welcome to Essentials of Prompt Engineering. In this course, you will be introduced to the fundamentals of crafting effective prompts. You will gain an understanding of how to refine and optimize prompts for a range of use cases. You will also explore techniques like:

* zero-shot,
* few-shot,
* and chain-of-thought prompting.

Finally, you will learn to identify potential risks associated with prompt engineering.

## Prompt Basics

### Understanding Prompts

Improving the way that you prompt a foundation model is the fastest way to harness the power of generative artificial intelligence (generative AI). By interacting with a model through a series of questions, statements, or instructions, you can adjust model output behavior based on the specific context of the output that you want to achieve.

Using effective prompt strategies can offer you the following benefits:

* Enhance the model's capabilities and bolster its safety measures.
* Equip the model with domain-specific knowledge and external tools without modifying its parameters or undergoing fine-tuning.
* Interact with language models to fully comprehend their potential.
* Obtain higher-quality outputs by providing higher-quality inputs.

In this lesson and the subsequent ones, you will learn about various prompt engineering methodologies. You will learn how to frame questions with greater precision, provide examples of desired outputs, suggest intermediate steps, and more.

#### Elements of a prompt

A prompt's form depends on the task that you are giving to a model. As you explore prompt engineering examples, you will review prompts containing some or all of the following elements:

* Instructions: This is a task for the large language model to do. It provides a task description or instruction for how the model should perform.
* Context: This is external information to guide the model.
* Input data: This is the input for which you want a response.
* Output indicator: This is the output type or format.

#### Negative prompting

Sometimes it's easier to guide a model toward a desired output by including what you don't want included in the output. Negative prompting is used to guide the model away from producing certain types of content or exhibiting specific behaviors. It involves providing the model with examples or instructions about what it should not generate or do.

For instance, in a text generation model, negative prompts could be used to prevent the model from producing hate speech, explicit content, or biased language. By specifying what the model should avoid, negative prompting helps steer the output towards more appropriate content.

### Modifying Prompts

Although foundation models (FMs) are generally highly capable, their outputs can be greatly influenced by the prompts provided. In this lesson, you will discover techniques for modifying and refining prompts to achieve better results. By the end of this lesson, you will have a solid understanding of how to tweak and optimize prompts, unlocking the full potential of generative AI models.

#### Inference parameters

When interacting with FMs, you can often configure inference parameters to limit or influence the model response. The parameters available to you will vary based on the model that you are using. Inference parameters fit into a range of categories, with the most common being randomness and diversity and length.

##### Randomness and diversity

This is the most common category of inference parameter. Randomness and diversity parameters influence the variation in generated responses by limiting the outputs to more likely outcomes or by changing the shape of the probability distribution of outputs. Three of the more common parameters are temperature, top k, and top p. Choose each to learn more.

##### Temperature

This parameter controls the randomness or creativity of the model's output. A higher temperature makes the output more diverse and unpredictable, and a lower temperature makes it more focused and predictable. Temperature is set between 0 and 1. The following are examples of different temperature settings.

##### Top P

Top p is a setting that controls the diversity of the text by limiting the number of words that the model can choose from based on their probabilities. Top p is also set on a scale from 0 to 1. The following are examples of different top p settings.

##### Top K

Top k limits the number of words to the top k most probable words, regardless of their percent probabilities. For instance, if top k is set to 50, the model will only consider the 50 most likely words for the next word in the sequence, even if those 50 words only make up a small portion of the total probability distribution.

#### Length

The length inference parameter category refers to the settings that control the maximum length of the generated output and specify the stop sequences that signal the end of the generation process. To learn more, choose each of the following parameters.

##### Maximum length

The maximum length setting determines the maximum number of tokens that the model can generate during the inference process. This parameter helps to prevent the model from generating excessive or infinite output, which could lead to resource exhaustion or undesirable behavior. The appropriate value for this setting depends on the specific task and the desired output length. For instance, in natural language generation tasks like text summarization or translation, the maximum length can be set based on the typical length of the target text. In open-ended generation tasks, such as creative writing or dialogue systems, a higher maximum length might be desirable to allow for more extended outputs.

##### Stop sequences

Stop sequences are special tokens or sequences of tokens that signal the model to stop generating further output. When the model encounters a stop sequence during the inference process, it will terminate the generation regardless of the maximum length setting. Stop sequences are particularly useful in tasks where the desired output length is variable or difficult to predict in advance. For example, in conversational artificial intelligence (AI) systems, the stop sequence could be an end-of-conversation token or a specific phrase that indicates the end of the response.

#### Best practices for prompting

Although inference parameters are important and clearly influence a model's output, they are mostly just settings that you can adjust as part of the prompting process. To craft an effective prompt, it's important to follow some best practices. The following are some useful tips for designing prompts.

##### Be clear and concise

Prompts should be straightforward and avoid ambiguity. Clear prompts lead to more coherent responses. Craft prompts with natural, flowing language and coherent sentence structure. Avoid isolated keywords and phrases.

##### Include context if needed

Provide any additional context that would help the model respond accurately. For example, if you ask a model to analyze a business, include information about the type of business. What does the company do? This type of detail in the input provides more relevant output. The context that you provide can be common across multiple inputs or specific to each input.

##### Use directives for the appropiate response type

If you want a particular output form, such as a summary, question, or poem, specify the response type directly. You can also limit responses by length, format, included information, excluded information, and more.

