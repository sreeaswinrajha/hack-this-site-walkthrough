# 🛠 Challenge Description

This time Network Security sam has saved the unencrypted level7 password in an obscurely named file saved in this very directory.
In other unrelated news, Sam has set up a script that returns the output from the UNIX cal command. 

___

#  Goal

To find the path of the file in which the password is saved
 ___

# 🧠 APPROACH

we can type the year which we want to view 

<img width="968" height="966" alt="Screenshot 2025-07-16 180346" src="https://github.com/user-attachments/assets/3f5a4945-ede6-4d66-90aa-04d4f23cd749" />

</br> let us try 2015

<img width="966" height="981" alt="Screenshot 2025-07-16 180417" src="https://github.com/user-attachments/assets/f5692f24-fc68-424e-8a89-d6e2313dd629" />

 </br> the result

 <img width="398" height="973" alt="Screenshot 2025-07-16 180425" src="https://github.com/user-attachments/assets/0ba70942-331c-4382-9fee-f2f8c71db5bb" />

</br> we can try command injection to list the files in the directory </br>

use ``2025;ls``

<img width="781" height="608" alt="Screenshot 2025-07-16 180454" src="https://github.com/user-attachments/assets/b20aaff4-8aa1-4601-bfab-e11231a4cdd3" />

</br> we can see the content of the files located in the directory </br>

<img width="193" height="138" alt="Screenshot 2025-07-16 180506" src="https://github.com/user-attachments/assets/3774df82-ab92-4aa1-81a1-1a47aab2225c" />

</br> here comes the password

<img width="996" height="159" alt="Screenshot 2025-07-16 180530" src="https://github.com/user-attachments/assets/d26d2770-2342-4201-996c-1b4e8c3202f6" />

___

# ✅ RESULT 

<img width="963" height="973" alt="Screenshot 2025-07-16 180633" src="https://github.com/user-attachments/assets/3a2ac98e-576b-409c-b6cb-1d6de6840c93" />


