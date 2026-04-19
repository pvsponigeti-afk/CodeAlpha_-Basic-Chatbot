def chatbot():
    while True:
        user = input("You: ").lower()

        if user == "hello":
            print("Bot: hey there")

        elif user == "how are you":
            print("Bot: i'm doing good")

        elif user == "exit":
            print("Bot: chat ended")
            break

chatbot()
