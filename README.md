# ArmyCTF-TicklePickle
  ArmyCTF-TicklePickle exploit and modified files.

Following changes have been made to make the code more secure : 
1. Encrypt the file with symmetric encryption
2. Client will set the permission to the key file and user.json
3. Check which user is running the program, so no third party can write the users.json file
