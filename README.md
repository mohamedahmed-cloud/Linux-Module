# Errors and Thing I learn from this project
----
## Some Resource Helped me in Learning Dealing with linux Modules

- [Youtube Vidoes](https://www.youtube.com/watch?v=S8hifIrDh-g&list=PL16941B715F5507C5)
- [Linux hint Website](https://linuxhint.com/)
- [linux comamnd](http://linuxcommand.org/lc3_lts0040.php)

---
##  Learning Ojbectives
- [X] What is the kernal and kernal Modules
- [X] Dealing with linux Directory in 
- [X] How to `insert` and `remove` new module and display modules message error if there is.
- [X] How to passing parameter to the Module
- [X] How to write first modules that print display message when linux modules `insert` and display another message when `remove`
- [X] Dealing with `jiffies` -> a kernel variable
- [X] Type of Device Drive in linux `character device` and `block device` and dealing with them.
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
- AFter all these error I make and edit on linux system module [didn't remember it's name] and error another error appear
- After That I remove `-dev` {that contain device files used for interacting with hardware devices or software interfaces} and reinstall, and that didn't make sense
- After that I remove header and install it here return to the first error appear
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

