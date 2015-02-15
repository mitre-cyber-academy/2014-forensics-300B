Name: Memory Dumps for Fun and Profit

Description: The user is told that we created a GUI in VB and were able to trace an IP. From that IP we obtained a very important password protected ZIP file and a memory dump of the PC. We know that the ZIP file and computer have the same password, so we need to extract the password from the memory dump to open the ZIP file.

Solution: There are many tools that can extract data from memory dumps. The one used while constructing the challenge is volatility. Using the commands given at [CyberArms](http://cyberarms.wordpress.com/2011/11/04/memory-forensics-how-to-pull-passwords-from-a-memory-dump/) you can get the password hash for the adiministrator account. Put the hash in a Windows XP password cracker, such as [OPHCrack](https://www.objectif-securite.ch/en/ophcrack.php) and get the password "Su94h S3cur3". Use the password to unlock the given ZIP file. The key is a watermark on an MP4.

Distribute: [challenge.zip](https://drive.google.com/file/d/0B48Lv30KB1seRkVZMnA3ZDdua28/view?usp=sharing)

Key: 22158853719ceab68292f03ee5d2e0428953021c