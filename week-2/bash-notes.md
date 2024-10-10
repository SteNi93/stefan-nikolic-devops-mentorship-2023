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