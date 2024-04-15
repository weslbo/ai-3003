# AI-3003 demo's

This repo hosts a number of demo's in the context of training AI-3003. 

- Analyzing text
    - [Language detection](/Analyzing%20text/01-Language%20detection.http)
    - [Key phrase extractions](/Analyzing%20text/02-Key%20phrase%20extraction.http)
    - [Sentiment analysis](/Analyzing%20text/03-Sentiment%20analysis.http)
    - [Named entity recognition](/Analyzing%20text/04-Named%20entity%20recognition.http)
    - [Entity linking](/Analyzing%20text/05-Entity%20Linking.http)
    - [Summarization](/Analyzing%20text/06-Summarization.http)
    - [PII Detection](/Analyzing%20text/07-PII%20detection.http) 
- Translating Text
    - [Detection](/Translating%20text/01-Detection.http)
    - [Translation](/Translating%20text/02-Translation.http)
    - [Transliteration](/Translating%20text/03-Transliteration.http)
    - [Word Alignment](/Translating%20text/04-Word%20Alignment.http)
    - [Sentence Length](/Translating%20text/05-Sentence%20Length.http)
    - [Profanity filtering](/Translating%20text/06-Profanity%20filtering.http)
- Build a question answering solution
    - [Q&A](/Q&A/01-q&a.http)
- Build a conversational language understanding app
    - [Conversation](/Conversational%20language/01-conversation.http)
- Custom classification and named entity extraction (TBD)
- Speech recognition, translation and synthesis (TBD)

## Required setup

- Provision resources in Azure (TBC)
    - Provision an **Azure AI Language** resource (F0 or S)
        - Make sure to select the **Custom question answering** block.
        - **Azure Search** pricing tier: Free (F)
    - Provision an **Azure AI Translator** resource (F0 or S)
    - Create a **question answering project** [(here)](https://github.com/MicrosoftLearning/mslearn-ai-language/blob/main/Instructions/Exercises/02-qna.md#create-a-question-answering-project)
    - Add sources to the knowledge base [(here)](https://github.com/MicrosoftLearning/mslearn-ai-language/blob/main/Instructions/Exercises/02-qna.md#add-sources-to-the-knowledge-base)
    - Add questions to the knowledge base [(here)](https://github.com/MicrosoftLearning/mslearn-ai-language/blob/main/Instructions/Exercises/02-qna.md#edit-the-knowledge-base)
    - Deploy the knowledge base [(here)](https://github.com/MicrosoftLearning/mslearn-ai-language/blob/main/Instructions/Exercises/02-qna.md#deploy-the-knowledge-base)
    - Create a conversational language understanding project [(here)](https://github.com/MicrosoftLearning/mslearn-ai-language/blob/main/Instructions/Exercises/03-language-understanding.md#create-a-conversational-language-understanding-project)


- Create a .env file in each folder and make sure the keys and endpoints are set correctly. You can use the sample.env files as a reference.