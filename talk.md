
def talk_to_bot():
greet_user()
while True:
user_input = input("Tú: ")
if "clima" in user_input.lower():
weather_response()
elif "deporte" in user_input.lower():
sports_response()
elif "película" in user_input.lower():
movies_response()
else:
general_response()


