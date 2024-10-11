# tpriyanshu60commits-countdown-timer
import time

my_time = int(input("enter the time in seconds-  "))

for x in range(my_time,0,-1):
    print(x)
    time.sleep(1)
print("time's up")
