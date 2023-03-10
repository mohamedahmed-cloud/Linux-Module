# Errors and Thing I learn from this project
----
## Some Resource Helped me in Learning Dealing with linux Modules

- [Youtube Vidoes](https://www.youtube.com/watch?v=S8hifIrDh-g&list=PL16941B715F5507C5)
- [Linux hint Website](https://linuxhint.com/)

---
##  Learning Ojbectives
- [X] What is the kernal and kernal Modules
- [X] How to passing parameter to the Module
- [X] Type of Device Drive in linux `character device` and `block device` and dealing with them.
- [X] How to write first modules that print display message when linux modules `insert` and display another message when `remove`
- [X] How to `insert` and `remove` new module and display modules message error if there is.
- [X] Dealing with linux Directory
- [ ]  Linux Kernel API
- [ ] Kernel module security

----
## Error That face me in Learning Journey and task

```bash

    sudo apt-get install linux-headers-$(uname -r)  #Here all thing is ok so I Make a reinstall for header
    sudo apt-get install --reinstall linux-headers-$(uname -r)  # The error is still exit so I upgrade my system to lastest version but error still exist
    sudo apt-get update && sudo apt-get upgrade #try to upgrade file system to last version but error still exit 
    #after all of these the error doesn't 
    
    
```
- AFter all these error I make and edit on linux system module[didn't remember it's name] and error another error appear
- After That I remove -dev and reinstall, and that didn't make sense
- After All of these try to remove header and install it here return to the first error appear
- After All of these I make a `dsemg` to see error message and copy and paste in stackoverflow and found the solution   
```py
    # I feel this condition happened with me
    while(1):
        print("error")
        stackoverflow.search("error Message 😂")
```

---
## Some resource helped me treating with error

- [one](https://www.linuxquestions.org/questions/linux-kernel-70/error-building-linux-kernel-module-invalid-module-format-4175704765/)
- [two](https://www.linuxquestions.org/questions/linux-software-2/invalid-module-format-when-insmod-the-kernel-module-4175481479/)

----
- 
