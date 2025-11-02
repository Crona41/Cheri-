from tkinter import *

# Create the main window
root = Tk()

# Set window title and dimensions
root.title("Sud0GUI")
root.geometry("300x150")

# Add a label widget
welcome_label = Label(root, text="hi!")
welcome_label.pack(pady=20) # Add some padding

# Add a button widget
def on_button_click():
    print("Button clicked!")

button = Button(root, text="Click Me", command=on_button_click)
button.pack()

# Start the Tkinter event loop
root.mainloop()
