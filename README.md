# Using Gemini to Interpret Machine Learning model

## Intentions
Create a proof of concept for using Gemini API to interpret a logistic regression model to explain how given input data resulted in a classification. Intended use-case would be to offer a detailed explanation to a non-technical user for why a model gave a certain output/prediction without requiring a data scientist to be present to answer questions.

## Reflections
Interacting with Gemini through code was actually much easier than I had expected. I know that API integrations with LLMs and other AI have become wildly common for numerous businesses, but still I wasn't really expecting a package that made it so simple where you essentially just have to drop in an API key (which was also incredibly easy to generate with the free tier) and the prompt. I was also expecting the response to be in JSON formatting, so the markdown format was a pleasant suprise, though I didn't take advantage of that and I'd imagine it wouldn't always be useful in other uses.

The data prep for the logistic regression being the most time-consuming piece wasn't what I was expecting, and I would've really loved it if I had been able to create a model that had more realistic accuracy, but since that wasn't the core focus of this notebook it served its purpose.
