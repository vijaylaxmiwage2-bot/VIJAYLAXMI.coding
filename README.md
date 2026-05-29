# VIJAYLAXMI.coding
"First Year CSE Undergraduate at [MVJ College of Engineering]. | 💻 Passionate about building scalable Backend systems and full-stack applications | Always learning, currently exploring [AI Technology] | Open to Software Engineering intern roles for 2026."
# Simple Hospital Chatbot

print("Welcome to Hospital Chatbot")

while True:

    user = input("You: ")

    if user == "doctor":
        print("Chatbot: Specialist doctors are available.")

    elif user == "timing":
        print("Chatbot: Hospital is open 24/7.")

    elif user == "appointment":
        print("Chatbot: Book appointment online.")

    elif user == "location":
        print("Chatbot: Hospital is located in Bangalore.")

    elif user == "exit":
        print("Chatbot: Goodbye!")
        break

    else:
        print("Chatbot: Sorry, I don't understand.")
