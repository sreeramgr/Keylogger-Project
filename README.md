This keylogger was built using Python's pynput library to capture keyboard events in real time and log them into a text file for authorized testing and educational purpose.


Step 1: The first step I have done is to import the dependecies. I have used [ from pynput import keyboard ] to handle key press and release events.


Step 2: Now, I have set the log file path where I created [key_log.txt] to store all captured keystrokes.

Step 3: Then, I have captured the key presses. For the normal keys i have logged the character [key.char]. Then for the special keys, I have logged their name [ ie [key.space], [key.caps_lock]].

Step 4: Next is detecting the key release. Here, i added a condition to stop the logger when [Esc] is pressed.

Step 5: Initializing and Start Listener. I used [keyboard.Listener] to start monitoring all key events until stopped. 

Step 6: When I run the script [python keylogger.py], the script begins recording keystrokes instantly.

Step 7: Testing and verify by typing an example text in another windows (i.e. Notepad). Confirmed all the keys including the special keys were saved in the [key_log.txt].

Step 8: Finally pressed "esc" to safely exit the program.


Below are the screenshots :

SS 1: 
<img width="1364" height="714" alt="Keylogger_code png" src="https://github.com/user-attachments/assets/59b9b847-ee2a-4073-b944-889de1bce7fc" />


SS 2:
<img width="1363" height="689" alt="Text_Input png" src="https://github.com/user-attachments/assets/76bdbe54-1b8a-478c-afe4-d1f742b64e8c" />


SS 3: 
<img width="1365" height="718" alt="Screenshot 3 Keylogger" src="https://github.com/user-attachments/assets/2393a91d-d5dd-4ad7-8db5-8deca1548787" />

