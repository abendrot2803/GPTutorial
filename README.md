
# GPTutorial

[Audio Tutorial Unity.docx](https://github.com/abendrot2803/GPTutorial/files/6354998/Audio.Tutorial.Unity.docx)


In this tutorial, you will learn how to add sound to your game object and invoke it using buttons in your unity project and control it using different functions. 

Step 1: Create the Game Object and Button GUI on which the audio will be played after clicking.

 ![1](https://user-images.githubusercontent.com/64202417/115645710-791a5200-a33e-11eb-9db3-b57f2aa3ad7b.png)


Step 2: Import an audio in your Unity Project. 


![2](https://user-images.githubusercontent.com/64202417/115645722-7ddf0600-a33e-11eb-840b-b7e3953df265.png)


Step 3: Link the audio to the Game Object.

![3](https://user-images.githubusercontent.com/64202417/115645733-83d4e700-a33e-11eb-9bd7-a5f9bf740bc6.png)

Step 4: Link the game object to the button by adding the game object in the onClick event of the button. 

![4](https://user-images.githubusercontent.com/64202417/115645739-88999b00-a33e-11eb-95ea-333d4620606a.png)

Step 5: To play the audio on clicking the button select the “audiosource” option in the functions and then select the play() option. You can select other options like pause(), playDelayed() etc as per your need.

![5](https://user-images.githubusercontent.com/64202417/115645770-94855d00-a33e-11eb-9aea-dfde2de49bea.png)


Step 6: We can also do this easily by adding the code to the game object. 

public AudioSource gameclip; 
public void playClip() 
{
gameclip = GetComponent();
gameclip.Play(); 
} 
} 


Step 7: Now we can click on the playclip() function that we created to play the sound. 

![7](https://user-images.githubusercontent.com/64202417/115645784-9b13d480-a33e-11eb-94bc-51e7efbb68db.png)





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


