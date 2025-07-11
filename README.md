# tkinter minimal styles

A quick and beginner level way to get modern, flat, dark and light theme on tkinter. 

You can easily change the colors at the top to customize. 


# Instructions

1. Copy the styles.py file and place it in the main directory of your new project.

2. In your main Python script, import the styles module. After creating your main application window, call the styles.apply_theme() function and save the returned color palette.

* You can select the theme by passing a mode argument:  
`palette = styles.apply_theme(root, mode='dark')` 

3. Use the saved palette dictionary to configure the colors of any other windows (like Toplevel pop-ups) or custom widgets. This ensures your entire application has a consistent look and feel.

* Example:  
`new_window = tk.Toplevel(root)`  
`new_window.configure(background=palette["BG"])`


# Samples

<img src="https://github.com/deminimis/tkinter_minimal_styles/blob/main/samples/darkpic.png?raw=true" alt="Dark Picture" style="max-width: 50%;">
<img src="https://github.com/deminimis/tkinter_minimal_styles/blob/main/samples/lightpic.png?raw=true" alt="Dark Picture" style="max-width: 50%;">
