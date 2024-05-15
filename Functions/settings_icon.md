This is the function of the drop down menu, once the user selects the settings icon, in the projects panel. Here is the code:

Set(showDropdown,!showDropdown);
If(
    showDropdown,
    ScreenTransition.Fade
)

The showDropdown is a boolean variable that was initiated in this icon. It is set to false to make it not show initially. 

I set the hidden menu to be 'showDropdown' for the true value. If the value is true then the menu shows.

- John Le
