# Web Track Project 1 - Character and Voice: Understanding Idiom and Grammar through Chatbots

## [Project Outline](https://coda.io/d/Web-Track-Design_dd0HU4GbwTC/Character-And-Voice-Understanding-Figurative-Language-through-Ch_su_fC#_lu6Ym)

## Project Description
In this project, students will explore the understanding of meaning through context, grammar usage and figurative language through the construction of chatbots. Using a fictional character and a topic of conversation as a base, users will construction user intents and bot responses a low-code chatbot framework and interact with that system’s API to a simple prebuilt web interface build in React. Could also result in an Alexa or messaging app integration.

## Project Technical Objectives
By the end of this project, students should be able to:
* Understand the chatbot construction and functioning
* Understand the concept of APIs, their use and basic Token Security
* Work with json data
* Experience building of how to build and chatbots within the SAP  Conversational Bot AI framework
* Understand how to use vanilla javascript to build a simple chatbot interface
* Understand how to use connect SAP to an external chat client

## Core Subject Objectives
By the end of this project, students should be able to:
* Understand and identify figures of speech, include: 
    - euphemisms
    - hyperbole
    - metaphor
    - simile
    - personification
    - understatement
* Identify run-on statements and word fragments
* Identify simple, compound and complex sentences
* Analysis text for sentence patterns and language consistency

For more information see [http://www.corestandards.org/ELA-Literacy/L/6/](http://www.corestandards.org/ELA-Literacy/L/6/)

## Course Progression
### Introduction to FSM
1. Introduce the Finite State Machines as a basic model for process design.

### Introduction to Chatbots
2. Introduce chatbot functioning in a FSM format.
    - Expressions as a base expression from a user.
    - An intent as a mapping from an expression or expression pattern to a common user intention.
    - An entity as a base type of information that can be extracted from an expression.
    - Memory is the place were conversation information can be stored.
    - A response as a statement given from the chatbot.
    - A redirection as a means to guide the conversation towards a specific path.
3. Have students create a basic chatbot within SAP
    - Navigate to https://cai.tools.sap/
    - Create new Account
    - Create new Perform Actions Bot > No Preset Skills > Non-Personal > Store > Non-vulnerable > Public
    - Build a New Intent called "Hello"
    - Add three expressions to the intent that all indicate hello.
    - Build a New Intent called "Goodbye"
    - Add three expressions to the intent that all indicate goodbye.
    - Run Train.
    - Note that we can use the test interface to test that the intent is found.
    - Note that changes in spelling and case can be accounted for.
    - Click on the build tab and create a new skill for greetings (mapped to hello) and signoff (mapped to goodbye)
    - Create 3 possible responses for each.
    - Test with the chatbot test interface.
4. Teach understanding of memory through entites
    - Add in a new Intent called "Get Name"
    - Within get name, add three responses and add in entities for extracting names.
    - Create skill get name and map the name entity.
    - Create the getname skill.
    - Detect the name entity and add it to conversation memory.
    - Add name to the getname response.
    - Add name, if in memory, to the goodbye skill.
5. Understand conditionals through response skills
    - Open up goodbye skill.
    - Add in conditional for if name exists or does not exist in memory.
    - Give one type or response for if name exists and one if not.
6. Construct a conversation flow from greetings to getname to goodbye.

### Understanding Integrations
1. SAP Conversation AI is an example of a Web based tool.
2. Introduce the idea of APIs as a kind of data version of a website.
3. You can send information to an API and get back a response you can use anywhere.
4. Introduce basic node and javascript.
5. Introduce axios.
6. Walk through how to make a request for a security token.
7. Walk through how to make a request for a chatbot response.
8. Do a basic tour of chatbot code contained with index.html and chatbot.js
9. Have student fill in needed info for connecting chatbot local code to SAP API.

### Understanding Character
1. Introduce the idea of character style and writing for a character. What makes a character sound the way that they do.
2. Introduce types of analysation:
    - Attitude (Positive, Negative, Neutral)
    - Repetition of phrase: (Frequent, Occasional, Never)
    - Sentence Length.
    - Word Length
    - Hyperbole Speech
    - Use of Metaphor / Simile
    - Use of understatement
    - Clause use (simple, compound or complex sentences)
    - Point of view (speaks in first person / third person)
2. Introduce Spongebob / Mr Crabs as an example using https://spongebob.fandom.com/wiki/Help_Wanted/transcript.
3. Introduce Thor as an example : https://transcripts.fandom.com/wiki/Thor:_Ragnarok
4. Introduce of a 100 year old person : https://www.youtube.com/watch?v=9AThycGCakk
5. Have students take a transcript of speech from a list or choose to transcript a person of their own. Create a profile of how to break down the character.

### Building Character Responses
1. Build a new chatbot that allows the character the student did an analysis to respond to the following base intents:
    - greetings
    - goodbye
    - get name
    - get age
    - get favorite film
    - get favorite color
    - responding to an insult
    - responding to a compliment
    - getting the time
    - telling where they are from
    - telling a joke
    - telling a story
    - responding to a laugh
    - responding to how they feel
    - responding to you feeling well
    - responding to you feeling bad
2. Have the chatbot be able to gather and use the following intents:
    - name
    - age
    - favorite color
    - favorite film
3. Have the chatbot respond approprately using text anylisis

### Expanding Integrations
1. Connect new chatbot to frontend code.
2. Walk through process to connect chatbot to Amazon Alexa.