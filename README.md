# git-and-github

# *Git & GitHub SSH Key Authentication Steps*

# Step-1
*open CMD and fire the following command.*

```bash
ssh-keygen -t rsa -b 4096 -C "your.email_id@gmail.com"
```
Note: Replace the email Id with your email 

# Step-2
#### *at default location 'C:\Users\user_name_of_pc\ .ssh' directory "id_rsa.pub" file will be available.*

# Step-3
*open id_rsa.pub file with text editor.*

#### copy full contents of file in clipboard

# Step-4
*Login to github -->> profile  -->> settings -->> SSH & GPS keys -->> new SSH key* 
#### give Title of the key
*use default key type(Authentication key)*
#### past key in text area

### *Finally click the button "Add SSH Key"*

*if everything is as done expected then you will see the following message.*
#### you have successfully added the key *'key_name'*
