1\. pwd printed my full current directory path (C:\\WINDOWS\\System32). It basically tells me exact spot where my terminal is currently sitting.



2\. ls -Force showed hidden files and dotfiles that regular ls hides by default, along with hidden system attributes.



3\. The Mode column showed the file attributes and permissions. in which 'd' stands for directory and 'a' stands for archive file.



4\. It works because coding-cafe\\week02 is a relative path starting from my current location (home dir), not like an absolute path starting from C:\\.



5\. mv did two things first it moved README-backup.md into the week01 directory, and then inside week01 it renamed README-backup.md to old-readme.md.



6\. Running the split command showed about 12 different folder paths saved in my PATH environment variable.



7.C:\\Users\\IMRAN AHMAD\\AppData\\Local\\Programs\\Python\\Python311\\python.exe



8\. Paths differ across machines because installation locations depend on individual user account names and custom install directories.

9\. The shell reported 'pyton is not recognized...'. This means pyton isn't an executable residing in any directory listed on my PATH, so Windows can't locate it.

10\. .venv starts with a period, so PowerShell flags it as a hidden directory. Standard ls skips hidden items unless -Force is appended.

11\. The command prompt updated to show (.venv) prepended at the very beginning of the line.

12\. No, Get-Command python now points inside .venv\\Scripts\\python.exe. Activate.ps1 showed the virtual environment path to the front of my PATH.

13\. The second output added requests alongside its required sub dependencies like urllib3, certifi, idna, and charset-normalizer.

14\. It points back to my main global Python executable outside the virtual environment.

15\. The -Recurse flag forces the command to traverse into all subdirectories recursively and list everything stored inside them.

16\. Ctrl + C forcibly stopped the running Python process immediately. Ctrl + Z sent an end-of-file (EOF) signal that exited Python cleanly after pressing Enter.

