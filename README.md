## Automate text messaging

 This code is an exampe to prank your friends and send them song lyrics.

You will notice a **'Message.txt'** file in the code. This `Message.txt` is a text file and should be stored in the same place as your python file. This text file will contain you message that you want to send.

You will find two python modules in the import section - `time and pyautogui`.
`time` module will help to send the message after 5 sec `(time.sleep(5))`. `pyautogui` is the module that will read the contents of the **Message.txt** file and write that to a specific place.

*```After pressing the "run" put your cursor to a file or a messaging app and wait for pyautogui module to start writing the contents for you.```

** ```Dont forget to put pyautogui.press('enter') otherwise your contents will be pasted in a single message.```
