# Basic Rule-Based Chatbot - by Manasa Munnuri
# Part of ai-engineer-journey

print("🤖 Hello! I am your Basic Chatbot")
print("Type 'bye' to exit\n")

while True:
    user_input = input("You: ").lower()

    if "hello" in user_input or "hi" in user_input:
        print("Bot: Hello! How can I help you?")
    
    elif "your name" in user_input:
        print("Bot: I am CodeBuddy, created by Manasa!")
    
    elif "python" in user_input:
        print("Bot: Python is a powerful language for AI Engineering!")
    
    elif "how are you" in user_input:
        print("Bot: I am doing great! Learning with you.")
    
    elif "project" in user_input or "github" in user_input:
        print("Bot: You can see all projects in your ai-engineer-journey repo!")

    elif "bye" in user_input or "exit" in user_input:
        print("Bot: Goodbye! Keep coding! 👋")
        break
    
    else:
        print("Bot: Sorry, I didn't understand. Try saying hello, python, your name")
