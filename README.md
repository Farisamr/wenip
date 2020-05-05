#welcome 
import os
print ("clear")
import socket 
import sys

print ("type your url:")
hostname=input()
ip = socket.gethostbyname(hostname)
print ("Host Name Is :",hostname, '\n''Target IP Is :' ,IP) 
