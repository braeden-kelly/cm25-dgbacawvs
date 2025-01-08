## Demystifying GenAI: Build A ChatGPT App with Vector Store

Welcome!  We will have 2 versions of the lab exercise: Python and/or Java, and all participants are welcome to try out either or both.

### Python
- Python 3 (consider installing with python virtual environment like pyenv)
- Python IDE of your choice (Visual Studio Code, PyCharm, etc.)
- Docker
- Langchain API key (to use LangSmith for debugging)

### Java
- Preferably using an IDE such as IntelliJ, VS Code, (or any equivalent tooling). CLI is okay too but you may need a bit of experimentation.J
- DK 17 or higher (can be any distribution from any vendor, such as the [OpenJDK/Adoptium](https://adoptium.net/), [Oracle distro](https://www.oracle.com/java/technologies/downloads/), etc)
- Maven 3.8 or higher (Gradle will be okay too if you prefer it)
_We'll be utilizing Spring AI and the online [spring initializr](https://start.spring.io) to generate the initial project 'frame', so the various library dependencies will be downloaded by default (including Spring Boot, Spring AI, Postgres with PgVector libraries...)

### OpenAI (applicable to both Python and Java, if we want to use any OpenAI models)
- OpenAI free account ([signup for new user](https://platform.openai.com/signup/))
- Obtain an Open AI Key (will require at least a small payment to start for model usages)

#### HuggingFace (OPTIONAL: only if interested, since we may be showing a few features there)
- HuggingFace Account ([signup for new user](https://huggingface.co/))
- AI-ML-Workshops community organization (OPTIONAL:  Please join our new [AI-ML-Workshops community organization](https://huggingface.co/AI-ML-workshops) for continuous info sharing and learning through the community, beyond the scope of this workshop)

#### Docker 
- If you prefer using Docker image for the DataStore or Database, instead of local installation.

#### Database and extension(s) (OPTIONAL: needed if not using Docker image and/or if you prefer manual or local installations)
- PostgreSQL  ([Download site](https://www.postgresql.org/download/))
- [PgVector vector extension](https://github.com/pgvector/pgvector/blob/master/README.md)

***Please check back here for more info, including the Workshop GitHub repo when the lab exercises are ready for you***
