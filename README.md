# AIChatbot
AI Chatbot which answers User’s queries/life problems by quoting examples from The Bhagavad Gita using Meta’s Llama 2 model.

# Usage
Set up your own API Key using the email id where the credits are available and paste that.
    os.environ['OPENAI_API_KEY'] = 'your-api-key'
Also create a hugggingface token with write access
    Site: https://huggingface.co/settings/tokens
    Use it during login whenever code demands.
![image](https://github.com/Muskan2307/AIChatbot/assets/93080620/2119c1cb-3bdb-4736-a119-38e2d05e3fb3)

# Integration with External Knowledge Base
This code is not creating/having its own knowledge base but can refer to any number of external links for reference.
URLs=[
    'https://www.radheradheje.com/culture-bhagavadgita-quotes-100-best-bhagavad-gita-quotes/'
]

# Examples/Test Cases
Test Case 1: Who lives in wisdom
Answer by chatbot: The wise men who have faith in Me, worship Me with this knowledge. Also, those who live in wisdom are those who see themselves in all and all in them. 
Furthermore, he who has faith and has mastered his sense, devoted to spiritual practices attains knowledge and having attained knowledge, he quickly attains supreme peace.

Test Case 2: What can we offer to Lord
Answer by chatbot: According to the Bhagavad Gita, we can offer our surrender, service, and work with the welfare of others in mind to the Lord. Chanting the name of the Lord is also considered an offering, 
as it creates a shield of protection and has the power to cure and bring peace. Ultimately, whatever path one may take, it leads to the Lord in the end. 
The Lord accepts the love and devotion of His devotees and enters into all aspects of creation. Udhdhava expressed his refuge and desire to remain forever faithful to the lotus feet of the Lord.
