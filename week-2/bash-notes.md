# Level 0

-   **ping** - I used this to get the IP behind bandit.labs.overthewire.org. Ultimately, this was not necessary, I was overthinking 
-   **ssh -p 2220 bandit0@16.16.163.126** - I used this to attempt to make an SSH connection to the bandit.labs.overthewire.org

# Level 1

-   **ls** - Used this command to list out all files/folders in pwd
-   **nano readme** - I used this command to open the readme file and get the password

# Level 2

-   **ls** - Used this command to list out all files/folders in pwd
-   **cat ./-** - I used this to get the password from file named '-'

# Level 3

-   **ls** - Used this command to list out all files/folders in pwd
- **nano spaces\ in\ this\ filename** - I used this to open the file

# Level 4

-   **ls** - Used this command to list out all files/folders in pwd
-   **find** - Used this to find all files within the inhere folder
-   **cat ./...Hiding-From-You** - Used this to get the passwrod from the ...Hiding-From-You file

# Level 5

-   **ls** - Used this command to list out all files/folders in pwd
-   **find** - Used this to find all files within the inhere folder
-   **cat** - Used cat on all files individually until i found the password 

# Level 6

-   **ls** - Used this command to list out all files/folders in pwd
-   **find** - Used this to find all files within the inhere folder
-   **ls -R -l -lh** - Used this to list all folders, subfolders and files within in a list format with human-readable format
-   **find . -type f - size 1033c** - Used this to find a file with a specific size
-   **cat ./maybehere07/.file2** - Used to get the password from a file

# Level 7

- **cd** - To navigate
- **find -type f -size 33c -user bandit7 -group bandit6** - To find a file with specified attributes

# Level 8

-   **ls** - Used this command to list out all files/folders in pwd
-   **nano data.txt** - To open data.txt
-   **grep -h millionth data.txt** - To display online the line which has word "millionth"

# Level 9

-   **ls** - Used this command to list out all files/folders in pwd
-   **nano data.txt** - To open data.txt
-   **sort data.txt** - To sort content of data.txt, it printed out sorted content without really sorting it
-   **uniq -u data.txt > pass.txt** - To write out the unique line appearing in data.txt to pass.txt > no permission
-   **sort data.txt | uniq -u** - To sort out and print the only unique line in data.txt

# Level 10

-   **ls** - Used this command to list out all files/folders in pwd
-   **cat data.txt** - To print the contet of data.txt to the terminal
-   **cat data.txt | grep -a ==** - I used this command to print out the specific lines of data.txt which have 2+ '==' signs as a pattern, this enabled me to see the       password immediately
-   **grep -a ===** - I tested this command to see whether I'd be able to find the password without it and it produced the same result