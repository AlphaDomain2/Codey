# Codey
    This website provides users with an interface to write HTML, CSS, and JavaScript code and see the output in real-time within an embedded iframe.
    
Header Section:

    The header contains the logo of the website and the title "Codey: A simple & interactive code editor."
    It also includes buttons for changing the views (layouts) and modes (light mode and dark mode).

Main Section:

    The main section is divided into two parts: the editor and the output.
    The editor allows users to input HTML, CSS, and JavaScript code in separate text areas.
    The output section displays the result of the code execution within an iframe.

Buttons Section:

    It contains a button labeled "Clear All" that allows users to clear all the code from the editor.

Footer Section:

    The footer provides information about the website and its creators.
    It also includes social media links to GitHub, LinkedIn, and YouTube.

How It Works:

    Code Editors:
        Users can input HTML, CSS, and JavaScript code in separate text areas.
        Each text area is associated with an onkeyup event listener, which triggers the run() function whenever the user types something.

    Output Display:
        The output is displayed in an iframe (<iframe>).
        The run() function takes the input from the HTML, CSS, and JavaScript text areas, combines them, and renders the output within the iframe.
        The run() function is called whenever there is a keyup event in any of the code input areas.

    View and Mode Switching:
        Users can switch between different view modes using buttons labeled "View 1," "View 2," and "View 3."
        View 1, View 2, and View 3 alter the layout of the editor and output sections to provide different perspectives.
        Users can also switch between light mode and dark mode using the corresponding buttons in the header.

    Clear All Button:
        The "Clear All" button, when clicked, clears all the content from the HTML, CSS, and JavaScript code input areas as well as resets the output iframe.

    Styling:
        The website is styled using CSS, which defines the layout, colors, and appearance of different elements.
        The website uses the Poppins font from Google Fonts for its typography.

Overall, Codey provides a simple and user-friendly interface for coding and observing the outcomes of HTML, CSS, and JavaScript code snippets in real-time.

This website is live at ->

        https://alphadomain2.github.io/Codey/
