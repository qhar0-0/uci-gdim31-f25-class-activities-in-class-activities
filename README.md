# in-class-activities
## Devlogs
### W1
When removing the camera from the Cat GameObject, the camera no longer follows the cat when the game is ran. This is because the camera follows whatever its parent object is.
Itch.io game link: https://doubledink2.itch.io/gdim-31-activity-w1
### W2
The r, g, and b variables are floats because rgb can only go up to 1.0 and thus the values of r, g, and b must be floats so they can be decimals or fractions in between 0.0 and 1.0;
The _bounce variable is an int rather than a bool, float, or string because it is a whole number representing the number of times the ball has bounced and thus must be an integer and not a float because you cannot have a decimal number of bounces. A bool only has 2 values: true and false, and thus cannot represent numbers. It also cannot be a string because it is not text but rather a variable integer that changes frequently. The main problem with the line of code was the fact that I subtracted 0.1 instead of 0.1f from g. The compiler could not understand what I was subtracting from g as there was no 'f' after the 0.1, causing the compiler to think I was subtracting a double rather than a float. 
### W3
Activity 1:
  Question 1:
    public string GetResponse(int friendshipLevel, bool secretRevealed)
    
  Question 2:
    public void SetLightDimness(float sanityLevel)
    
  Question 3:
    public bool DidPlayerHitBeat(float timeHit)

    
Activity 2:
  
  Classes are an instructional handbook for assembling a PC (component) with the parts being the member variables and instructions being the methods


Activity 3:

  The balls get extremely bright especially if they bounce too many times because the line where we use the GetCOlorMultiplier method increases the brightness of the ball that bounces since it is within the OnCollisionEnter2D method and that activates whenever the ball bounces. Therefore, the more the ball bounces, the brighter its color will become.



## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
