Chapter 20
## 1. How can you trigger PyAutoGUI’s fail-safe to stop a program?
We can quickly slide the mouse to one of the four corners of the screen. PyAutoGUI function call has a 10th-of-a-second delay after performing its action to give you enough time to move the mouse to a corner. If PyAutoGUI then finds that the mouse cursor is in a corner, it raises the pyautogui.FailSafeException exception.
##  2. What function returns the current resolution()?
cr = pyautogui.size() # Obtain the screen resolution.

## 3. What function returns the coordinates for the mouse cursor’s current position?
 pyautogui.position() 
 ## 4. What is the difference between pyautogui.moveTo() and pyautogui.move()?
 pyautogui.move()- Moves cursor relative to current position
  pyautogui.moveTo()- Moves to a specific position on the screen.
 ## 5. What functions can be used to drag the mouse?
 pyautogui.dragTo() 
 
  pyautogui.drag() 
  ## 6. What function call will type out the characters of "Hello, world!"?
  pyautogui.write('Hello, world!')
  ## 7. How can you do keypresses for special keys such as the keyboard’s left arrow key?
  pyautogui.keyLeft()
  ## 8. How can you save the current contents of the screen to an image file named screenshot.png?
   im = pyautogui.screenshot()
   ## 9. What code would set a two-second pause after every PyAutoGUI function call?
   pyautogui.sleep(2)   
   ## 12. How can you find the size of every window on the screen that includes the text Notepad in its title?
sr = pyautogui.size()
##  13. How can you make, say, the Firefox browser active and in front of every other window on the screen?
pyautogui.getActiveWindow()









  








  
 









