# Challenge : GITHUB

#### 		**Category : Forensics**

Author : *Paul* 	[<u>@cyberpj</u> ](twitter.com/cyberpj1)

Solution :

1. After unzipping the github.zip , there is was  lots of  folder and files

- **Don't get into rabbit hole like **
  - `diff or git -show or git logs. :)`
-  **BE BEGGINER ** :smile_cat:**
- The flag Was Splitted into several pieces

2. *Just Enum the folder*

   - First Part : /github/logs/refs 

     - `TamilCTF{`

   - Second Part : /github/logs/refs/heads 

     - `i_d0nt_`

   - Third Part :  /github/branches 

     - `kn0w_4b0u7`

   - Fourth Flag was protected by the Password 

   - [**The Password Was Stored In "config" File**]

     - `cat config |tail`
     - ["last one pwd=tamilctf2021"]

   - Yeah , 

     ```
     ┌──(p4ul㉿none)-[~/ctf/tamil-ctf/github/]
     └─$ unzip -P "tamilctf2021" index.zip
     Archive : index.zip
     	extracting:index
     ```

   - Cat The *index* , It contains the last part

     - `_g!7_:(`

   -  **github/** contain a file '}'  was the Ending Part :)

   - That's all ,Flag Formed   :happy:

   - `flag : TamilCTF{i_d0nt_kn0w_4b0u7_g!7_:(}`

   **Thank You **

   ​		By *TAMILCTF TEAM*











