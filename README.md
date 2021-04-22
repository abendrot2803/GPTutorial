# GPTutorial


# GPTutorial

In this tutorial, you will learn how to add sound to your game object and invoke it using buttons in your unity project and control it using different functions. 

Step 1: Create the Game Object and Button GUI on which the audio will be played after clicking.

 
# GPTutorial

In this tutorial, you will learn how to add sound to your game object and invoke it using buttons in your unity project and control it using different functions. 

Step 1: Create the Game Object and Button GUI on which the audio will be played after clicking.

 

Step 2: Import an audio in your Unity Project. 




Step 3: Link the audio to the Game Object.



Step 4: Link the game object to the button by adding the game object in the onClick event of the button. 



Step 5: To play the audio on clicking the button select the “audiosource” option in the functions and then select the play() option. You can select other options like pause(), playDelayed() etc as per your need.



Step 6: We can also do this easily by adding the code to the game object. 

public AudioSource gameclip; 
public void playClip() 
{
gameclip = GetComponent();
gameclip.Play(); 
} 
} 

Step 7: Now we can click on the playclip() function that we created to play the sound. 




Step 2: Import an audio in your Unity Project. 




Step 3: Link the audio to the Game Object.



Step 4: Link the game object to the button by adding the game object in the onClick event of the button. 



Step 5: To play the audio on clicking the button select the “audiosource” option in the functions and then select the play() option. You can select other options like pause(), playDelayed() etc as per your need.



Step 6: We can also do this easily by adding the code to the game object. 

public AudioSource gameclip; 
public void playClip() 
{
gameclip = GetComponent();
gameclip.Play(); 
} 
} 

Step 7: Now we can click on the playclip() function that we created to play the sound. 


