# 🛠 Challenge Description


Sam remains confident that an obscured password file is still the best idea, but he screwed up with the calendar program. Sam has saved the unencrypted password file in /var/www/hackthissite.org/html/missions/basic/8/
However, Sam's young daughter Stephanie has just learned to program in PHP. She's talented for her age, but she knows nothing about security. She recently learned about saving files, and she wrote a script to demonstrate
her ability.

___

#  Goal

To locate the file containing the password, we must leverage Server Side Includes (SSI) for directory traversal, as standard path navigation is restricted.

 ___

# 🧠 APPROACH

To understand how **Server Side Includes (SSI)** can be exploited and how they work, refer to the OWASP documentation below.

- 🔗 [OWASP - Server Side Includes (SSI) Injection](https://owasp.org/www-community/attacks/Server-Side_Includes_(SSI)_Injection)

<img width="767" height="355" alt="Screenshot 2025-07-20 161633" src="https://github.com/user-attachments/assets/96fbdb47-3155-4a21-b815-fd68aa51e896" />

</br> let us try 
</br>``<!--#exec cmd="ls ../" -->``

<img width="768" height="290" alt="Screenshot 2025-07-20 162557" src="https://github.com/user-attachments/assets/896c8bf5-4085-43f5-8820-400c20833706" />

</br> so it now shows the path

<img width="959" height="137" alt="Screenshot 2025-07-16 210359" src="https://github.com/user-attachments/assets/2d5ca1c4-75c0-42f7-a4ec-2e450ed23ffa" />

</br> and it the directory we can see the password

<img width="1532" height="122" alt="Screenshot 2025-07-16 210349" src="https://github.com/user-attachments/assets/6bd19440-1419-4a47-8657-923ce4556dc6" />

___

# ✅ RESULT 

<img width="859" height="227" alt="Screenshot 2025-07-16 210829" src="https://github.com/user-attachments/assets/c7950317-c23e-401b-9982-7bbbf4c4ae33" />


