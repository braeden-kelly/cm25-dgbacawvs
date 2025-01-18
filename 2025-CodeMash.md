## Demystifying GenAI: Build A ChatGPT App with Vector Store

Welcome!  We will have 2 versions of the lab exercise: Python and/or Java, and all participants are welcome to try out either or both.

### Python
- Python 3 (consider installing with python virtual environment like pyenv)
- Python IDE of your choice (Visual Studio Code, PyCharm, etc.)
- Docker
- OpenAI API key (see instructions below)
- Langchain API key to use LangSmith for debugging (optional). To create account and API key, refer to these [instructions](https://docs.smith.langchain.com/administration/how_to_guides/organization_management/create_account_api_key#create-an-account).
- If you're using Windows, install Git Bash so that you can run the commands below (if using VSCode you can select Git Bash after starting the integrated terminal)

 #### Repos:
 #### HelloWorld and The Meal Planner Apps:
 - [https://github.com/braeden-kelly/codemash2025-demystifying-genai-build-a-chatgpt-app-with-vector-meal-planner-chatbot](https://github.com/braeden-kelly/codemash2025-demystifying-genai-build-a-chatgpt-app-with-vector-meal-planner-chatbot)

### Java
- Preferably using an IDE such as IntelliJ, VS Code, (or any equivalent tooling). CLI is okay too but you may need a bit of experimentation.J
- DK 17 or higher (can be any distribution from any vendor, such as the [OpenJDK/Adoptium](https://adoptium.net/), [Oracle distro](https://www.oracle.com/java/technologies/downloads/), etc)
- Maven 3.8 or higher (Gradle will be okay too if you prefer it)
_We'll be utilizing Spring AI and the online [spring initializr](https://start.spring.io) to generate the initial project 'frame', so the various library dependencies will be downloaded by default (including Spring Boot, Spring AI, Postgres with PgVector libraries...)
- Spring AI reference materials can be found in [here](https://docs.spring.io/spring-ai/reference/)

  #### Repos:
  ##### HelloWorld (very basic Spring AI examples):
  - OpenAI  [https://github.com/ai-ml-workshops/ai-openai-helloworld](https://github.com/ai-ml-workshops/ai-openai-helloworld)
  - Ollama  [https://github.com/ai-ml-workshops/ai-ollama-helloworld](https://github.com/ai-ml-workshops/ai-ollama-helloworld)
  ##### RAG example (SpringAI, PgVector with Docker):
  - Spring AI RAG sample (from Dan Vega)[https://www.danvega.dev/blog/2024/10/22/getting-started-with-spring-ai-rag#building-your-first-rag-application]

### C#

- Visual Studio 2022
- .NET 8
- OpenAI API key (see instructions below)

 #### Repos:
 [OpenAI Hello World example with C#](https://github.com/ai-ml-workshops/openai-csharp-helloworld)

### OpenAI API key (needed for any project using any OpenAI model)

- Create an OpenAI free account ([signup for new user](https://platform.openai.com/signup/)).
- **You must add money to your account before generating an Open AI Key.** The minimum amount of $5 should be sufficient. 
  - You can verify your balance on the [billing dashboard](https://platform.openai.com/settings/organization/billing/overview). Make sure you see "Auto recharge is off" below your balance, so that it doesn't automatically charge you when you run out of balance.
- Generate OpenAI key

This [website](https://coding-boot-camp.github.io/full-stack/ai/openai-account-setup-guide) has good step-by-step instructions.

#### HuggingFace (OPTIONAL: only if interested, since we may be showing a few features there)
- HuggingFace Account ([signup for new user](https://huggingface.co/))
- AI-ML-Workshops community organization (OPTIONAL:  Please join our new [AI-ML-Workshops community organization](https://huggingface.co/AI-ML-workshops) for continuous info sharing and learning through the community, beyond the scope of this workshop)

#### Docker 
- If you prefer using Docker image for the DataStore or Database, instead of local installation.

#### Database and extension(s) (OPTIONAL: needed if not using Docker image and/or if you prefer manual or local installations)
- PostgreSQL  ([Download site](https://www.postgresql.org/download/))
- [PgVector vector extension](https://github.com/pgvector/pgvector/blob/master/README.md)

***Please check back here for more info, including the Workshop GitHub repo when the lab exercises are ready for you***

## **Presentation Slide Deck: https://bit.ly/4fHZDoC**

