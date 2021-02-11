# -Python-Project-1
#1 Username and password (Hidden)

username = input("Please, type your username\n")
password = input("Please, type your password\n")
password_length = len(password)
hidden_password = password_length * '*'

print(f"Hello {username} !, your password, {hidden_password}, is {password_length} letters long.")
