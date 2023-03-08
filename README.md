# Day30
Creating good and strong passwords is a little bit challenging. You create a password today only to forget it during the week. This program helps you by creating a strong password for you and stores it for you safely.

## Lessons learned today

- Errors
- Exception
```
try:
    file = open('file_name.txt') as data_file:
except FileNotFoundError:
    file = open('file_name.txt')
else:
    content = file.read()
    print(content)
finally:
    file.close()
    print("filewas closed")
```
- Saving JSON data
   #### writing:
        ```
        json.duump(new_data,file_data,indentation=4)
        ```
    #### Reading:
        ```
        json.load(file_name)
        ```
    #### Updating:
        ```
        json.update(previous_data,file_name,indent=4)
        ```
## Project to solidify material learned: 

### Preview:
![password1](./pass1.png)
![password](./pass2.png)



### Password_tracker


> Creating good and strong passwords is a little bit challenging. You create a password today only to forget it during the week. This program helps you by creating a strong password for you and stores it for you safely.  The user can also search for their passwords for a particular website... Built with tkinter ..



## How to run this on your device

- Clone this repository
```
git clone https://github.com/kingdreamerr/Day30_password_tracker_improved.git
```
- cd into the repo
```
cd Day30_password_tracker_improved
```

- Paste the following in the terminal 
```
python3 main.py
```