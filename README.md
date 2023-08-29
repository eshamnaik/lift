# lift
This is the LIFT SIMULATION PROJECT that get genarated till 3floors and has 2 lifts.
At the start the user gets the page where he/she has to input the number of floors and lifts.
On clicking the simulate button,the second page is displayed on the screen.
In this page Up and Down button is been present, by clicking that the lift starts to move.
Each floor has up and down button,by clicking that the lift starts to simulate and goes to the floor where it is been called.
When u click on the BACK button the user is been taken to the first page.

Features-
This lift generates only upto 3 floors and has only 2 lifts.
The lift gates opens and closes at 2.5s , and moves up and down in 5.5s. 

Functions-
querySelector- This method is called on the document object to select elements.
addEventListener-is a function that "listens" for a specific event to occur on the selected element and then it executes a specified code when that event happens.
hideSecondPage()- Hides the second page of the simulation interface and shows the first page.
makingFloors()- Generates the floors and elevators based on user inputs and sets up event listeners for user interactions.
moveLift(liftno, floorNo, oldFloorValue)- Animates the movement of an elevator to a specified floor, including door animations and a delay before making the elevator available again.
gateopenclose(liftno)- Simulates the opening and closing of elevator doors using CSS transitions.
deletingFloors()- Removes the floor divs from the interface, effectively resetting the simulation when restarting.
