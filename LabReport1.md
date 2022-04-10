# Installing VSCODE

1. To install VS Code:
  - Go to https://code.visualstudio.com/
  - Click the download option that best suits your operating system.
  - After installtion this window should pop up ![Click here](<img width="1440" alt="Screen Shot 2022-04-01 at 2 21 26 PM" src="https://user-images.githubusercontent.com/103288210/162635487-5f86e277-390a-4426-aa01-163911635dd6.png">
)
2. To remotely connect to the ieng6 server
  -Open the Terminal on VS Code by pressing `Ctrl + `
  - Next, enter ssh cs15lsp22zz@ieng6.ucsd.edu in the terminal by replacing zz by your account specific letters.
  - Enter the `yes` key to the question "are you sure you want to keep connecting?"
  - Enter your account password when prompted
  - Your terminal should look like this:![CLICK](<img width="1068" alt="Screen Shot 2022-04-01 at 2 27 08 PM" src="https://user-images.githubusercontent.com/103288210/162635748-799a9af3-71ce-4825-8023-f47969096cf1.png">
)
  - Congratulations, you have succesfully logged in!
3. Begin experimenting wiht some terminal commands, here is an example of what I did:
![alt text](<img width="1440" alt="Screen Shot 2022-04-01 at 2 37 57 PM" src="https://user-images.githubusercontent.com/103288210/162635865-de8947e6-f135-48e9-812c-476143f8690c.png">
)
4. To move files over computers, use the command `scp`
  - Create a filename.java
  - Place whatever code you want to run in the body
  - Run the file on the terminal using java and javac
  - Run the following code onto your termianl `scp WhereAmI.java cs15lsp22zz@ieng6.ucsd.edu:~/`, again by replacing the zz with your account specific letters.`
  - Enter your password
  - Login to your course account using the ssh command as follows: ssh cs15lsp22zz@ieng6.ucsd.edu
  - This is what your terminal should look like if done successfully:
  ![Press to view](im<img width="1440" alt="Screen Shot 2022-04-01 at 2 37 57 PM" src="https://user-images.githubusercontent.com/103288210/162636168-8720b3e8-6b94-4e27-be12-34418e08afe4.png">
age.jpg)
5. Set an SSH key, to avoid entering password every time
  - On your computer type `ssh-keygen`, and wait for public key to generate
  ![It will look like this](<img width="700" alt="Screen Shot 2022-04-10 at 12 31 58 PM" src="https://user-images.githubusercontent.com/103288210/162636499-5bd66a69-983d-4801-a241-6e9b6d8b6b11.png">)
  - to copy ssh key, type `ssh cs15lsp22zz@ieng6.ucsd.edu`
  - Follow the following on the screen ![Press](<img width="803" alt="Screen Shot 2022-04-10 at 12 38 17 PM" src="https://user-images.githubusercontent.com/103288210/162636702-1675b569-8187-4964-96be-8272ccb6ce7b.png">)
  - Now try logging into your account again, and observe!
  ![No passowrd was needed!](<img width="687" alt="Screen Shot 2022-04-10 at 12 41 02 PM" src="https://user-images.githubusercontent.com/103288210/162636779-cf2db3bd-28f2-4457-a98a-8b15201efa05.png">)


  
  

