#Brief description of the model 0 in English

This model tries to understand how new, or virgin, words appear in a language. I'm going to start from the following idea:

* We have a network of agents that  will exchange  the words.
* Agents can sometimes act as issuer of the word and sometimes as receiver.
* We have a global language is a set of words.
* We have local languages, which will be the set of words possessed by each agent
* Inicialemente all local languages will be equal to the global language.
* In every interaction that makes the emisor agent  you can choose a word of their language and invent another
* In every interaction the receptor agent can accept or not the word that gives the emisor agent. This depends if you already know it or not.
* If the word was new, meaning that the emisor agent did not have it in their local language, and the receptor agent does not accept, then the emisor agent does not keep it in your local language. If the receptor agent accepts it then the new word will be keeped by both.
* As interactions happen several new words that reach out to be in a certain number of local languages will be added to global language.
* We will study every few interactions if a new word appears in a new global language for different network structures.
* For that,  we will develop in python classes for agents, language, network and anything more.
* In results we will generate images with graphs and tables csv.
