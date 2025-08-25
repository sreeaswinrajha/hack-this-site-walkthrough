# 🛠 Challenge Description

Network Security Sam is going down with the ship - he's determined to keep obscuring the password file, no matter how many times people manage to recover it. This time the file is saved in 
/var/www/hackthissite.org/html/missions/basic/9/. 
In the last level, however, in my attempt to limit people to using server side includes to display the directory listing to level 8 only, I have mistakenly screwed up somewhere.. there is 
a way to get the obscured level 9 password. See if you can figure out how..

___

#  Goal

To locate the file containing the password, we must leverage Server Side Includes (SSI) for directory traversal, as standard path navigation is restricted.

___

# 🧠 APPROACH

we need to move to previous page this page doesn't allow SSIR
<img width="787" height="330" alt="Screenshot 2025-07-19 194259" src="https://github.com/user-attachments/assets/ebc6746e-b363-43c2-8b8c-2aac023b73e1" />


we inseted the payload in this page now we can see the page in which is pass is saved

<img width="784" height="212" alt="Screenshot 2025-07-19 194431" src="https://github.com/user-attachments/assets/964bffbf-bcb8-46aa-a878-3f773fe40638" />


now it shows us the pages sumbsomain adress

<img width="588" height="74" alt="Screenshot 2025-07-19 194444" src="https://github.com/user-attachments/assets/e8086208-9bc9-4314-9b54-b56aadb1ef49" />

and wala password 😃

<img width="281" height="69" alt="Screenshot 2025-07-19 194530" src="https://github.com/user-attachments/assets/243a3a7e-61c2-438b-964b-367669979f61" />


___

# ✅ RESULT 

<img width="991" height="972" alt="Screenshot 2025-07-19 195153" src="https://github.com/user-attachments/assets/c577bac6-9da2-4305-8470-2ae17a4d57b1" />

