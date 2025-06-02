Password Genie - Random Password Generator
Overview
Password Genie is a web-based random password generator designed to create strong, customizable passwords. It offers a user-friendly interface with vibrant colors and a modern feel, allowing users to specify password length and character types. It also includes an "easy to remember" option that excludes ambiguous characters.

Features
Customizable Password Length: Users can select a password length between 4 and 64 characters using an intuitive slider.

Character Type Selection:

Include Uppercase Letters (A-Z)

Include Lowercase Letters (a-z)

Include Numbers (0-9)

Include Special Characters (!@#$%^&*()_+-=[]{}|;:',.<>/?~)

Easy to Remember Option: When selected, the generator uses modified character sets that exclude visually similar characters (e.g., 'l', '1', 'I', 'O', '0') and a simpler set of special characters.

Instant Generation: Passwords are generated client-side immediately upon changing options or clicking the "Generate Password" button.

Copy to Clipboard: A convenient "Copy" button allows users to quickly copy the generated password to their clipboard.

Responsive Design: The application is designed to work well on various screen sizes, from mobile to desktop.

Modern UI: Features a vibrant gradient background, a slightly transparent card with backdrop blur, and modern-looking UI elements.

User Feedback: Provides messages for actions like copying to the clipboard or errors (e.g., if no character types are selected).

How to Use
Open the Application: Launch the index.html file in a web browser.

Set Password Length: Adjust the slider to choose your desired password length. The current length is displayed next to the slider.

Select Character Types:

Check the boxes for "Uppercase," "Lowercase," "Numbers," and "Special" characters according to your requirements.

At least one character type must be selected.

(Optional) Easy to Remember:

Check the "Easy to Remember" box if you want a password that avoids ambiguous characters.

Generate Password:

The password will automatically update as you change options.

You can also click the "Generate Password" button.

View Password: The generated password will appear in the "Your Secure Password" display area.

Copy Password: Click the "Copy" button next to the password display. A notification will confirm that the password has been copied.

Technologies Used
HTML: Structure of the web page.

Tailwind CSS: Utility-first CSS framework for styling and responsive design.

Custom CSS is also used for specific styling enhancements (e.g., gradients, component-specific looks).

JavaScript: Handles the password generation logic, UI interactions (slider, checkboxes, button clicks), and copy-to-clipboard functionality.

Google Fonts (Poppins): Used for a modern and clean typography.

File Structure
index.html: The main HTML file containing the structure, styles (inline and Tailwind), and JavaScript logic for the password generator.

Customization Notes
Character Sets: The JavaScript code defines character sets for ALL_LOWERCASE, ALL_UPPERCASE, ALL_NUMBERS, ALL_SPECIAL, and their "easy to remember" counterparts (EASY_LOWERCASE, etc.). These can be modified to change the pool of available characters.

Styling: Most styling is handled by Tailwind CSS classes directly in the HTML. Custom styles are within the <style> tags in the <head> section of the index.html file. These can be adjusted to change the visual appearance.

Error Handling
The application will display an error message if no character types are selected.

It will also display an error if the chosen password length is too short to accommodate at least one character from each selected character type.
