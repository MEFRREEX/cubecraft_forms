# Forms documentation

![image](https://user-images.githubusercontent.com/83061703/202968771-69dcac6e-205f-4d0b-bd6f-38198fb78852.png)
Title: ```is_dynamic&side_text<title text>```  
Buttons: ```grid_tile<button name>```  

# 
![image](https://user-images.githubusercontent.com/83061703/202969365-f4f1c063-3146-428f-8402-1bbefa8def25.png)
Title: ```is_dynamic&side_text<title text>```  
Buttons: ```grid_tile<button name>```  
Header buttons: ```header_button<§s§r[button name]>```

# 
![image](https://user-images.githubusercontent.com/83061703/202970775-5119837d-e7a3-408d-98c5-4c317bb5c952.png)
Title: ```is_dynamic&small_grid&grid_text<title text>```  
Rect buttons: ```rect_button<button name>```  
Buttons: ```grid_tile<button name>```  
Header buttons: ```header_button<§s§r[button name]>```

  
![image](https://user-images.githubusercontent.com/83061703/202971792-a61ab216-ecb8-4f3e-8be0-fb90713ed039.png)
Title ```is_dynamic&big_button&stack_text<title text>```  
Big button: ```big_button<button name>```  
Button: ```grid_tile<button name>```  
Header buttons: ```header_button<§s§r[button name]>```

  
![image](https://user-images.githubusercontent.com/83061703/202972785-25ecf8d1-244a-4d98-9712-4430d29a5d07.png)
(In this form, the sequence of buttons matters)
Title ```is_dynamic&big_button&stack_text<title text>```  
Big button: ```big_button<button name>```  
Rect button: ```rect_button<§t§rbutton name>```
Header buttons: ```header_button<§s§r[button name]>```  
**REQUIRED: 3 blank buttons (No text, no pictures)**
**Here they act as spaces and line breaks.**
**Depending on the number of buttons and the type of buttons, the number of empty buttons may vary.**
Button one: ```grid_tile<button name>```  
Button two: ```grid_tile<button name>```  

  
# Additional parameters for buttons
```§s§r``` - the text will be displayed only when hovering over the button  
```§t§r``` - will make the rectangular button larger  
```§w§r``` - the button will change color to white  
```§g§r``` - the button will change color to gold  
How to use: ```button_parameter<add_parameters[text]>```

