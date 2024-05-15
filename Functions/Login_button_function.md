Complete code for the login button function:

If(
    !IsBlank(
        LookUp(
            'Username list',
            Usernames = Username_input.Text && Passwords = Password_input.Text
        )
    ),
    Navigate(Success, ScreenTransition.Fade),
    Navigate(Fail, ScreenTransition.Fade)
)

So to break it down, this function means that if the username input field has the exact same characters as the sharepoint data associated with this user will allow the user to navigate to the success screen, with a transition animation added. Although, in order to login, both the username and password must be equal to the sharepoint account that is present or signed up to.
