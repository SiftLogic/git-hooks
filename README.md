git-hooks
=========

Useful hooks for git

##commit-msg - Enforce structure of commit message
To use, either copy or symlink the commit-msg file to/from your .git/hooks/ folder
###Format: (TYPE) [ACTION] #ISSUE SUMMARY [empty line] DESCRIPTION

+ TYPE any of the following in parens  
feature, feat, bugfix, fix, task, doc, docs, release, changelog, chore, refactor
+ ACTION [optional]  
fix, fixes, fixed, close, closes, closed, resolve, resolves, resolved
+ \#ISSUE  
This can be a github issue number e.g #123 or #+ one of the following: spelling, typo, whitespace  
e.g.s #123, #whitespace, #typo
+ SUMMARY  
This is for a short summary of the commit
+ DESCRIPTION  
The description should be separated from the 1st row with an empty line and fully address the commit
###Examples
    (bugfix) closes #123 Fixed the bug  
    
    Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam  
    nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat  
    volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation  
    ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.  
    Duis autem vel eum iriure dolor in hendrerit in vulputate velit  
    esse molestie consequat


    (feature) #123 Added new option  
    
    Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam  
    nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat  
    volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation  
    ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.  
    Duis autem vel eum iriure dolor in hendrerit in vulputate velit  
    esse molestie consequat




