# projects
# This is the pseudocode for the Haunted House project I did in JAVA/Netbeans.
#Haunted House Tester class:
•	Contains the main
•	HauntedHouse haunted = new HauntedHouse(); serves as the object for linking my tester class with my regular HauntedHouse class.
•	JOptionPane.showInputDialog(); then asks the user for their name to then welcome them to the game. 
•	Then I called upon the Door(); method to begin game by using haunted.Door(); 
Haunted House class:
•	Begins with correct imports to support images and JOptionPane.
•	Getter/Setter to receive user’s name.
•	Created 12 private instance variables to represent User’s choices they make throughout my Haunted House when they choose what they want to do. 
•	Next, made each room it’s own method to avoid unneccesary nested if statements.
•	Within each method, I first include the ImageIcon syntax to show User a picture of what room they are in at that current moment. 
•	After the image is shown to the User, JOptionPane.showInputDialog(); is used to ask User where they want to go (What they choose is represented by choice1, choice2, choice3, etc instance variables. 
•	First method = Door();
o	Asks user from the door, where they want to go (Living room, Dining room, upstairs)
o	From their choice, I used an if-else statement to represent which direction they took. For example, if (choice1.equals(“Living room”) 
{
     Living room();
}
•	Then for each ROOM, I called that specific room’s METHOD.
•	User had the option to explore a room’s objects if they wanted to or backtrack. 
•	If User explored an item, I gave them a description of what happened when they came across that item and lastly, showed them a picture indicating what room they ended the game in.
•	Side note: Most of my items cause the User to die.
•	If User wanted to go back to a room they were already in, I provided that option by asking them to type in “Go back to *room name*” in JOptionPane.showInputDialog(); and called upon that method. 
•	The winning route is towards the Master bedroom’s shower. 
•	Last method = UpstairsBathroom(); 
