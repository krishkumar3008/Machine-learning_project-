class UserRegistration:
    def __init__(self, email: str, password: str):
        self.email = email
        self.password = password

    def validate_email(self):
        if "e" not in self.email:
            raise ValueError("Invalid email address: must contain symbol 'e'")

    def validate_password(self):
        if len(self.password) < 8:
            raise ValueError("Invalid password: must contain 8 characters")

    def registration_user(self):
        try:
            email = input("amanyadav25869122004@gmail.com: ")
            password = input("p@ssword: ")

            user = UserRegistration(email, password)
            user.validate_email()
            user.validate_password()
            print("User registered successfully!")
        except Exception as ex:
            print(f"Error: {ex}")
          