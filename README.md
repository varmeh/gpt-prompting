# ChatGPT Prompts
Prompts Inputs by ChatGPT

## Prompt Parameters

When communicating with a language model, several factors can be specified to shape the conversation. Here are a few key parameters:

| Parameter            | Description                                                                                           | Example Input                                                                                                  |
|----------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| Objective            | State the goal or purpose of the conversation.                                                        | "I want to learn about the history of the internet."                                                           |
| [Persona](./docs/persona.md)              | Specify a role for the AI to assume during the conversation.                                          | "Act as a detective from a noir film."                                                                        |
| [Tone](./docs/tone.md)                 | Indicate the desired tone of the conversation (e.g., formal, informal, friendly, serious, humorous). | "Use a humorous tone."                                                                                        |
| Answer Format        | Different formats in which answers could be generated                                                 | "Give me your answers in Q&A format with bullet points, case studies & analogies"                                |
| Response Size        | Specify the desired length of the responses (e.g., brief, detailed).                                  | "Give me a summary of the French Revolution."                                                           |
| Technicality Level   | Request responses that match your expertise in a subject (e.g., beginner, intermediate, expert).    | "Explain the concept of black holes at an intermediate level."                                                |
| Citation Preferences | State preferences for sources and references in responses.                                            | "Include citations from scientific journals."                                                                 |
| Bias and Neutrality  | Indicate if you want responses to be neutral, balanced, or from a specific viewpoint.                | "Give me a balanced overview of the arguments for and against climate change."                                |

| Contextual Information | Provide background information or context about the topic of conversation.                          | "I have just started learning about programming and would like to understand the difference between Python and Java." |

You can use these parameters to guide the conversation and get responses that are more tailored to your preferences and needs.

Here's an example template that incorporates these parameters:

```
Objective: To learn about the history of machine learning
Persona: Act as a university machine learning professor
Tone: Formal and educational.
Answer Format: Q&A format with bullet points, case study & analogies
Response Size: Detailed

Technicality Level: Intermediate.
Citation Preferences: Include references to scientific papers and books.
Bias and Neutrality: Present a balanced view of historical developments.

Contextual Information: I am a professional software developer with 10 years of experience in full stack development but I have absolutely no prior understanding of machine learning.
So, please explain in as detail as possible while drawing analogies from backend development. 

[Start of conversation]
```

This template would instruct the model to provide detailed, educational responses about the history of quantum mechanics with references and a balanced view as if you are in a university lecture.

Feel free to mix and match these parameters based on your needs, and let me know if you have any questions or need further clarification!

*Note*: Of all the parameters metioned, following parameters would be sparsely used:
- `Citation Preferences`
- `Bias & Neutrality`
- `Technicality Level` - Usely convered while giving contextual information.

## Parameter Effect

These parameters effect different aspects of a response.

The same has been captured in next table:

| Key Parameter  | Part of the Response Affected   | Description and Examples                                                                                                             |
|----------------|--------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Objective      | Content, Focus                 | Defines the main goal or purpose of the response. For example, if the objective is to educate, the content will be informative and detailed. If the objective is to entertain, the content may be humorous or engaging.        |
| Persona        | Personality, Voice             | Affects the character traits and style that is portrayed in the response. For example, a teacher persona might be educational and patient, while a comedian persona might be humorous and witty.|
| Tone           | Tone, Style                    | Affects the manner in which the content is delivered. For example, a formal tone may use professional language, while a friendly tone might be more conversational.                           |
| Answer Format  | Structure, Organization        | Determines how the information is presented. For example, a bullet-point format will list information, while a Q&A format will present information in a question-and-answer style.         |
| Response Size  | Length, Detail                 | Determines the amount of information given in a response. For example, a concise response may provide a brief answer, while an extensive response would go into more detail.                 |


These parameters can be used in combination to tailor the responses to specific needs and preferences. For example, if you want a detailed and informative response with a friendly tone, you might specify an educational objective, a friendly tone, an extensive response size, and a teacher persona.

## Parameter Default Values

The default values for the key parameters are as follows:

| Key Parameter  | Default Value   | Description                                                                                                             |
|----------------|-----------------|-------------------------------------------------------------------------------------------------------------------------|
| Objective      | General         | If no specific objective is stated, the response aims to provide general information or assistance based on the query. |
| Persona        | None            | The default persona is neutral. The language model doesn't adopt a specific personality or traits unless instructed to do so.|
| Tone           | Neutral/Formal  | The default tone is typically neutral or formal, focusing on delivering information without any specific stylistic tone.|
| Response Size  | Medium          | Responses are usually of medium length, providing enough information to answer the query without being overly extensive.|
| Answer Format  | Paragraph       | Information is generally provided in a paragraph format unless a different format is requested.                        |

It's important to note that these defaults are designed to provide balanced and informative responses in a wide range of situations. 

However, the parameters can be adjusted to meet specific needs or preferences.

## GPT Best Practices

Above parameters, when combined with [GPT Best Practices](https://platform.openai.com/docs/guides/gpt-best-practices) yield best results.