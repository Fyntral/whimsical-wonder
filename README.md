import random

# Lists of whimsical elements
characters = ["a wise old owl", "a mischievous pixie", "a clumsy giant", "a curious cat", "a brave little mouse"]
settings = ["in a magical forest", "at the bottom of the sea", "on a floating island", "inside a giant pumpkin", "in a hidden valley"]
objects = ["a golden key", "an enchanted book", "a mysterious map", "a glowing crystal", "a talking teacup"]
actions = ["found", "lost", "discovered", "stumbled upon", "was given"]

# Function to generate a whimsical story
def generate_story():
    character = random.choice(characters)
    setting = random.choice(settings)
    obj = random.choice(objects)
    action = random.choice(actions)

    story = f"One day, {character} {action} {obj} {setting}. And that was just the beginning of a fantastical adventure!"
    return story

# Generate and print a whimsical story
print(generate_story())
