# Article

A basic article generator by giving ta subject as prompt with an additional web search feature via Google Serp. History of chats is also saved.


# Steps to run locally

1. Run
2. `cd generator`
3. Install all required libraries `pip install -r requirements.txt`
4. Provide OpenAI API key to the env by running `export OPENAI_API_KEY=your_key`
5. Run `streamlit run app.py` to see it working.

Voici comment va fonctionner l’application :

L’utilisateur entre un sujet et appuie sur le bouton générer

Voici mon hypothèse pour les agents langchain.

source_agent : 
L’application va rechercher 3 sources en lien sur le web à travers des articles.

writer_agent :
L’application va résumer ces articles.

content_agent
L’application va générer un article sur le thème en tenant compte des résumés des articles précédent.# articlegenerator
# articlegenerator
