
# GPTutorial

[Audio Tutorial Unity.docx](https://github.com/abendrot2803/GPTutorial/files/6354998/Audio.Tutorial.Unity.docx)


In this tutorial, you will learn how to add sound to your game object and invoke it using buttons in your unity project and control it using different functions. 

Step 1: Create the Game Object and Button GUI on which the audio will be played after clicking.

![1](https://user-images.githubusercontent.com/64202417/115660828-323a5580-a35a-11eb-8c8e-fd5667daa10d.jpeg)

Step 2: Import an audio in your Unity Project. 

![2](https://user-images.githubusercontent.com/64202417/115660863-3c5c5400-a35a-11eb-9e24-a66e8606848f.jpeg)

Step 3: Link the audio to the Game Object.

![3](https://user-images.githubusercontent.com/64202417/115660906-49794300-a35a-11eb-8283-6a1d1fa1c26d.jpeg)

Step 4: Link the game object to the button by adding the game object in the onClick event of the button. 

![4](https://user-images.githubusercontent.com/64202417/115660931-526a1480-a35a-11eb-9b47-c2bc01a627c0.jpeg)

Step 5: To play the audio on clicking the button select the “audiosource” option in the functions and then select the play() option. You can select other options like pause(), playDelayed() etc as per your need.

![5](https://user-images.githubusercontent.com/64202417/115660951-5b5ae600-a35a-11eb-96ad-cc811d6d7d45.jpeg)

Step 6: We can also do this easily by adding the code to the game object. 

public AudioSource gameclip; 
public void playClip() 
{
gameclip = GetComponent();
gameclip.Play(); 
} 
} 


Step 7: Now we can click on the playclip() function that we created to play the sound. 

![7](https://user-images.githubusercontent.com/64202417/115660983-69a90200-a35a-11eb-848f-bc70006499d2.jpeg)


