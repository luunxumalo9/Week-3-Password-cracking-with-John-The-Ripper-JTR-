### Password Cracking With Networkwalks Tools
As part of week 3 of my cybersecurity internship at Networkwalks, i recovered the passwords of locked PDFs using Networkwalks free browser-based tools no installation required.

## Tools Used
- Networkwalks Hash Calculator
- Networkwalks Password Cracker

## Steps
1. Uploaded the locked PDF ('My Locked PDF1.pdf') to the Hash Calculator to extract its hash
2. Copied then resulting has
3. Pasted the hash into the Password Cracker
4. Recovered password

## Results
Successfully cracked the PDF password using only browswer-based tools. A good beginner-friendly  alternatives to command-line tools like John The Ripper.

### Password Cracking With Joh The Ripper (Kali Linux)
I also completed the equivalent task using John The Ripper (JTR) and Johnny GUI on Kali Linux.

## Enviroment 
- Kali Linux VM (VirtualBox)
- John The Ripper (John)/ Johnny GUI

  ## Steps
  1 Extracted the hash from the locked PDF using 'pdf2john.py'
  *python3 pdf2john.py<file>.pdf>hash.txt*
  2 Ran John The Ripper against the hash
  *john hash.txt*
  3 Viewed the cracked password
  *john --show hash.txt*
  4 Recovered password.

  ## Results
  Successfully cracked the PDF password using JTR on Kali Linux.

  ### Note
All files used were provided by Networkwalks Academy for training purposes only.
This exercise  was completed strickly for educational purposes as part of a supervised internship program.
