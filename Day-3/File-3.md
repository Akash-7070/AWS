# How to run cpp code on linix

## STEPS:

### 1) Check gcc is installed or not
  * run `gcc -v` 
  if is gives
  * `gcc: command not found`
  then run 
  * `sudo su yum -y gcc-c++`
  
  ![check gcc](https://github.com/Akash-7070/AWS/blob/master/Day-3/Images/1.PNG)
 
 -------
### 2) Now check gcc tool is installed or not 
* `gcc -v`
 
 ![Check gcc](https://github.com/Akash-7070/AWS/blob/master/Day-3/Images/2.PNG)

---------
### 3) Make directory
* `mkdir`

![Make directory](https://github.com/Akash-7070/AWS/blob/master/Day-3/Images/3.PNG)

-------
### 4) Create CPP file 
* `vi Demo.cpp`

![create editor](https://github.com/Akash-7070/AWS/blob/master/Day-3/Images/4.PNG)

---------
### 5) Enable code
    * `press i`
 ----------
### 6) Enter code
 ---------
### 7) press 
* `esc`
 --------
### 8) press 

* `:wq` to save and exit (w= save and q=exit)

------
### 9) Compile code 
* `g++ Demo.cpp -o Demo`


![compile code](https://github.com/Akash-7070/AWS/blob/master/Day-3/Images/5.PNG)

---------
### 10) Run code 
* `./Demo.cpp`


![Run code](https://github.com/Akash-7070/AWS/blob/master/Day-3/Images/6.PNG)
 
