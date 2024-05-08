# The script of the game goes in this file.

# Declare characters used by this game. The color argument colorizes the
# name of the character.

define k = Character("Kody")

default viewed = 0

# The game starts here.

label start:

    scene Introduction

    k "Hello, my name is Kody Fike."

    k "I am here to talk to you today about the goals that I want to achieve as someone who is taking the Game Design Master’s degree at Full Sail University."

    scene Overarching Goal

    k "I want to talk about what I want my end goal for my career to be."

    k "I want to lead a team and make an encounter in a game with the equivalent design properties and principles of a Raid in an MMORPG."

    k "To design and create this with a team and watch how others interact with what I have designed is a big goal and I would like to see it on a large scale."

    scene Graduation Goal

    k "Now I want to talk about what I want when I graduate from Full Sail. I want a position with a game company solidified."

    k "I know this will be a difficult goal, but I want to take this step to get my career started for the first time and I will do my best to do it."

    k "This does mean I have to set goals for myself to reach and here is what I plan on doing to achieve this."

    k "Each time you click on one of the prompts I will explain why it is a goal of mine."

    k "You will only see one at first, but each time you read one it will add a new one to simulate a timeline."

    k "You can also go back and read them at any point if you want if you ever want to."

    scene Strategies

    menu strategies:
        
        "1. Learn The Tools of The Trade":
            jump tools
        
        "2. Get into a Programming track" if (viewed >= 1):
            jump programming

        "3. Find Another Field I Might be Interested in Trying" if (viewed >= 2):
            jump find_field

        "4. Solidify My Connections" if (viewed >= 3):
            jump connections

        "5. Lead a Team" if (viewed >= 4):
            jump lead

        "6. Redo my Resume" if (viewed >= 5):
            jump resume

        "7. Land the Job" if (viewed >= 6):
            jump job

        "Continue..." if (viewed >= 7):
            call reflection

    return

label tools:
    scene Learn The Tools of The Trade

    k "I do have a background with a good amount of the tools that are used in game development."

    k "This does not mean I know every tool within the development process, however."

    k "A good example is what I used to create this."

    k "I am very new to Ren’Py and this has been a good challenge for me to learn some of the elements within a short amount of time. "

    k "There will be even more technologies introduced to me over time during my time at Full Sail and I am excited to learn more about them."

    if viewed == 0:
        $ viewed += 1

    scene Strategies

    jump strategies

label programming:
    scene Get into a Programming Track

    k "This is probably one of the base goals that I have for myself initially for this degree."

    k "I want to get into a programming track and just show others what I am capable of."

    k "This does not mean I will lock myself to this track,"

    k "but it will be the best starting way of allowing myself to potentially find other fields that I might be interested in since this is the most comfortable field for me."

    if viewed == 1:
        $ viewed += 1

    scene Strategies

    jump strategies

label find_field:
    scene Find Another Field I Might be Interested in Trying

    k "I don’t necessarily want to lock myself to just programming"

    k "Game development has many facets to it and there is so much that I might be able to do. "

    k "I want to see if there is a potential other avenue for me to explore even if it might not be for me in the end."

    k "I want to give it a try."

    if viewed == 2:
        $ viewed += 1

    scene Strategies

    jump strategies

label connections:
    scene Solidify My Connections

    k "Early on I want to solidify those that I want to interact with and show them what I am capable of."

    k "This step will be constant throughout, but it is essential to me."

    k "I could potentially make friends through this process and also make great business connections as well."

    k "There is so much I can do to set a good impression on others, and I will take all the steps that I can to ensure that I make these impressions last."

    if viewed == 3:
        $ viewed += 1

    scene Strategies

    jump strategies

label lead:
    scene Lead a Team

    k "This is probably one of the biggest goals that I have within this program. I want to lead a team."

    k "This program gives many opportunities to lead a group potentially."

    k "I have led teams in the past, but I have not had the opportunity to do so in a professional setting."

    k "This will probably be the closest I have been to having the opportunity and I will take it with stride, and this will be a great step toward my overarching goal."

    if viewed == 4:
        $ viewed += 1

    scene Strategies

    jump strategies

label resume:
    scene Redo my Resume

    k "With the new experiences I have gained, I will be able to update and enhance my resume even further."

    k "This will allow me to be able to have a lot more confidence for when I apply to a role companies will see that I have been putting in the effort that I need to succeed."

    if viewed == 5:
        $ viewed += 1

    scene Strategies

    jump strategies

label job:
    scene Land the Job
    
    k "This is probably my most ambitious and exciting part for myself."

    k "I want to fully send myself to opportunities that come by so that when I graduate, I am all ready to take a step into my career."

    k "It won’t be easy, and I may also fail, but I intend to use both the career resources of Full Sail and all the connections that I have made to make it happen."

    k "The experience that I receive while here will help me out a lot and I will put my all into this so that I can be proud of what I have accomplished."

    if viewed == 6:
        $ viewed += 1
    
    scene Strategies

    jump strategies

label reflection:

    scene Reflection

    k "While at Full Sail there is plenty, there is still so much that I can do to achieve these goals. "

    k "I want to get into tutoring."

    k "I know there are a lot of students in the Bachelor’s field and even the Game Design Master’s field who might not be the best at coding. "

    k "I want to be able to help bridge that gap and create a connection with others through me being able to help them."

    k "I also want to explore the clubs at some point."

    k "I might be an online student, but I want to see if there might be something I can do club-wise where I can participate and be more involved in the community."

    k "Needless to say, I want to interact and engage with people, and I feel like this school will give me the opportunity to do so."

    jump conclusion

label conclusion:

    scene Conclusion

    k "This is just the start of my journey, and I am very excited about it. I feel as though I have made a good choice in coming here."

    k "This class has already taught me a lot and has solidified my ideas in how I approach my work."

    k "Mastery by Robert Greene was a great lead and just helped me realize I was on the right path."

    k "I plan on being adaptable and dedicated to this field I am going in."

    k "I will search for the problems I want to solve and take them on in stride."

    k "I am ready to take this step in my career."

    "References: Greene, R. (2013). Mastery. Penguin Books."

    return