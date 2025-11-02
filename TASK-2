import random

secret_number = random.randint(1, 100)
attempts = 0

print("🎯 Welcome to the Number Guessing Game!")
print("I'm thinking of a number between 1 and 100.")

while True:
    try:
        # Take user input
        guess = int(input("Enter your guess: "))
        attempts += 1

        # Compare the guess with the secret number
        if guess < secret_number:
            print("Too low! Try again.")
        elif guess > secret_number:
            print("Too high! Try again.")
        else:
            print(f"🎉 Congratulations! You guessed the number {secret_number} correctly in {attempts} attempts.")
            break
    except ValueError:
        print("❗ Please enter a valid number.")

