import base64
import time

print (''' 
            This is a very basic python program to decode base64 encoded data.
            With it you can see JWT info sent by the ALB to the targets. 
            All you need to do is to copy and paste the base64 string and 
            put into the box below and the decoder would produce the output
            
            ''')

def DECODE_BASE64():
    encoded = input ("Please paste the copied base64 data: ")
    decoded = base64.b64decode(encoded)
    print ("The Decoded base64 data is {} ".format (decoded))
    time.sleep (2)

while True:
    try:
        DECODE_BASE64()
    except:
        print ("ERROR: Sorry there was an issue with your base64 encoded data, can you please check and confirm that you have the right input data")
        time.sleep(2)






