# cmd-not-found-brew
## A solution to getting error: zsh: command not found: brew

###### Step 0: Open Terminal

###### Step 1: Install brew with this code
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

###### Step 2: check if brew is installed using code:
    brew help
    
###### Step 3: if you get an error saying command not found:
###### Find your mac user name and note it down
###### Copy and paste the next line into your mac os terminal 
    echo 'eval $(/opt/homebrew/bin/brew shellenv)' >> /Users/"YOUR MAC OS UserName"/.zprofile


###### Step 4: Copy and Paste the next line of code
    eval $(/opt/homebrew/bin/brew shellenv)


###### Step 5: Type into terminal the following code to check if you were able to get brew installed properly
    brew help
