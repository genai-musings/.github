# genai-musings - README.md

Recently I spent sometime spent experimenting with a number of generative AI text, image and video creation tools including ChatGPT, D-ID Studio, Dall-E and Bing Image Creator via the API interfaces they provide.

Sharing the results of those experiments through this, the genai-musings GitHub organization, which includes a number of sample repositories containing "bare bones" examples illustrating how to make a single API call to an AI tool and how to process the response.

- [chatting-with-ChatGPT](https://github.com/genai-musings/chatting-with-ChatGPT)

- [creating-with-BingImageCreator](https://github.com/genai-musings/creating-with-BingImageCreator)

- [dallying-with-DALL-E](https://github.com/genai-musings/dallying-with-DALL-E)

- [dawdling-with-D-ID](https://github.com/genai-musings/dawdling-with-D-ID)

Each repository also include the necessary GitHub CI Actions to lint, validate and test any code submitted before it is merged and a GitHub CD Action to build and deploy a docker image containing the respective sample applications.

Note: The sample repositories require accounts, keys and credits in some cases for the respective AI tools. Details as to what is required is specified in the README.md files of the individual repositories in the organization.

Finally upon noticing a common pattern emerging when creating those repositories, this organization also contains a GitHub Template Repository -[template-repo-template](https://github.com/genai-musings/template-repo-template) - this is a template Python repository intended for use if and when creating similar repositories for other AI tools or indeed when creating new Python repositories.

Feel free to browse the code, to make a contribution, or to ask a question by opening an issue in the relevant GitHub repository.
