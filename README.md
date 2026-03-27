# Micro-Rhythm-Microcontroller-Music-Project
A rhythm-based game using Bluetooth input, LCD prompts, servo movement, and speaker audio playback.

Original conceptualization: I wanted to create a rhythm game where the player has to stay focused and hit the correct inputs at the right time.

Description: The speakers are used to play a song, specificallyiItsy bitsy spider. While the song plays, the LCD board displays text telling the player which direction to input. The Bluetooth mechanic is used so the player can enter values representing “Up,” “Left,” and “Right.” When these inputs are entered, they change the direction of the servo, which has an arrow attached to it.
When the board tells the player what to input and the correct input is entered on time, the LCD briefly displays “Great.” If the player inputs the wrong direction or misses the timing, it displays “Fail” and shows the score out of 10. If all ten notes are hit correctly, the LCD displays “AMAZING! 10/10” and rewards the player with a short victory jingle.

Difficulties: The main difficulty at first was figuring out how to get the speakers working. After adjusting my port functions, I was able to get them to work properly. The next challenge was allowing both the servo and the speakers to work at the same time. I solved this by using a Bluetooth function within the speaker’s playnote() function, which allowed both components to work together. After that, things went much more smoothly, and testing went well. Overall, this project was a great learning experience and was fun to build.

Unfornately my code and video on this project was lost. Only a picture can be provided.
