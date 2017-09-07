# Take-a-Break
This project will remind a person who spends hours and hours on the computer to take  a Break and go Relax
import time
import webbrowser

total_breaks = 3
break_count = 0

print("the program started at"+time.ctime())
while(break_count < total_breaks):
    time.sleep(15)    
    webbrowser.open("https://www.youtube.com/watch?v=WpwMkC5GqoA")
    break_count = break_count + 1
