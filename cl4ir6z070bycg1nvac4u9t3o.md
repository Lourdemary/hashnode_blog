## Day 03 of 100 Days Of Code in Data Analytics : Data Validation in Excel

Excel's Data Validation feature allows you to limit the types of data that may be entered into a cell. You may limit the user to just entering a certain range of numbers, text, or dates. 


### NOTE
There are three scenarios in which you might wish to utilise Excel's Data Validation feature:
1. When you wish to limit data entry to specific numbers, language, or dates. It is not permitted to use data that does not match the validation requirements.
2. When you want to notify the user when data is entered that is out of range. However, any type of data entry is permitted.
3. When you show the user how to enter data. There are no restrictions on the kind of data that can be entered.

### Tab of Settings
![Screenshot (149).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655485488652/CTNmJ9o58.png align="left")
The validation criteria are entered in the settings tab. There are eight different ways to verify user input:

1. Any Value - It eliminates any data validation that was previously in place.
2. Whole Number - Only whole numbers are allowed. You can, for example, require the user to provide a value between 0 and 30.
3. Decimal - A number with decimal values must be entered.
4. List - The user must build a drop-down list from which to pick.
5. Date - The date format must be entered by the user.
6. Time - The user must provide a time.
7. Text Length - It verifies data depending on how long it is.
8. Custom - It uses a custom formula to verify the user input.

### Tab of Input Message
You may use the input message to specify what type of data is permitted in each cell. This tab is completely optional.
![Screenshot (150).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655485719076/Ht7Y-NQcS.png align="left")
1. Check the box that says "show input message when the cell is selected"
2. Give your work a title.
3. Enter a message in the input box.

### Tab of Error Alert
If the user tries to input incorrect data, you can display an error message.
On the tab for error messages, 
1. Select the option labelled "Show error alert after invalid data is entered"
2. Give your work a title.
3. Type an error message in the box provided.

The Error Alert tab in the Data Validation dialogue box allows you to personalise the error message. There are three possibilities:
1. Stop Error – Shows a stop error and prevents the user from entering data that is outside of the set range.
![Screenshot (151).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655485980783/uwbGqAjSH.png align="left")
2. Warning Error - Shows a warning message but allows the user to submit data that is outside of the designated range.
![Screenshot (152).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655486061892/QvJvOcMVF.png align="left")
3. Information Error - Shows an information error but allows the user to submit data that is outside of the set range.
![Screenshot (153).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655486073439/AKngp_1Fu.png align="left")

### Example to validate text
![Screenshot (156).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655487189068/9tplWY0Zw.png align="left")
To set up text validation, follow these steps:
1. Choose the cells where the data validation will be applied.
2. Use the shortcut - ALT+A+V+V
2. Select "text length" from the allowable dropdown.
3. Data: Between
4. Minimum: 3
5. Maximum: 15
6. press the OK button
![Screenshot (155).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655486822175/q5Hbp1FuV.png align="left")


### Acknowledgement 
This blog simply represents my own ideas and opinions (based on my limited knowledge) and should not be used as a replacement for legitimate sources. I'd welcome corrections in the comments if I ever make a mistake or if you disagree!

### End note 
These were the things that I was able to explore today, and I am looking forward to doing additional hands-on learning tomorrow. If you have any further information on the aforementioned concepts, please share it in the comments section below. Don't forget to connect me on [Twitter](https://twitter.com/datanomadd) and [Github](https://github.com/Lourdemary/100_Days_Of_Data).

Have a great time !
