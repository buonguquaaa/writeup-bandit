# writeup-bandit

#Lever 0

Level Goal: The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

Level này ta cần login được vào ssh server với host là bandit.labs.overthewire.org account bandit0:bandit0 ở port 2220

ssh bandit0@bandit.labs.overthewire.org -p 2220 với pass là bandit0

![image](https://github.com/user-attachments/assets/c57b6a71-efd2-4865-b78c-60cc67a44b14)


#Level 0 → Level 1

Level Goal: The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

Lever này ta chỉ cần đọc file readme bằng cat là xong

![image](https://github.com/user-attachments/assets/f70035d9-d376-4774-bc03-af88bf9d6f10)

Pass: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If


#Level 1 → Level 2

Level Goal: The password for the next level is stored in a file called - located in the home directory

Login lại ssh server với user là bandit1 và password lấy từ level trước, sẽ có một file là -.
Vì tên file đặc biệt nên không thể mở bằng cách thông thường vì cat hiểu rằng đọc từ bàn phím (standard input).
Đọc file có tên đúng là "-" trong thư mục hiện tại

![image](https://github.com/user-attachments/assets/9b83dc8e-c452-4a63-b495-11dadb4f8fed)

Pass: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx


#Level 2 -> Level 3

Level Goal: The password for the next level is stored in a file called spaces in this filename located in the home directory



Level Goal: The password for the next level is stored in a file called spaces in this filename located in the home directory

