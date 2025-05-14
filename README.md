# Scene-Development-Assignment
What changes I made: I made 2 alterations to the code provided, 1st being a change in the jumpspeed value to alter the height of jump, and 2nd being an addition to the code with a boolean value that checks for ground underneath the player to prevent infinite jumping

Challenges I Faced; one of the issues i faced was that the obstycle code provided did not function as intended showing this error message "Assets/player.cs(40,10): error CS0111: Type 'PlayerController' already defines a member called 'Update' with the same parameter types." As a result of this I wasn't able to press play. I believe others faced a similar issue with the code, I just couldn't find an answer at the time. My only other issue was that my character would spin like a fidget spinner and jump infinitely when interacting with objects and clicking jump concecutively.

How I solved these issues: I couldn't find a solution to this obstycle code as I didn't understand what the error message meant. However, to solve the issues with the player I used a constraint to lock the rotation of the Z axis and implemented a boolean value to detect if there was ground beneath by character, preventing the spinning issue and the infineitely jumping issue.

What was I most pround of in my game so far: I was most pround of how I was able to prevent my character from jumping without ground beneath it, eliminating infinite jumps.
