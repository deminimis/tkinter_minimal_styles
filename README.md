# tkinter minimal styles

A quick and beginner level way to get modern, flat, dark and light theme on tkinter. 


# Instructions

1. Copy the styles.py file and place it in the main directory of your new project.

2. In your main Python script, import the styles module. After creating your main application window, call the styles.apply_theme() function and save the returned color palette.

You can select the theme by passing a mode argument: 
palette = styles.apply_theme(root, mode='dark') 

3. Use the saved palette dictionary to configure the colors of any other windows (like Toplevel pop-ups) or custom widgets. This ensures your entire application has a consistent look and feel.

new_window = tk.Toplevel(root)
new_window.configure(background=palette["BG"])
