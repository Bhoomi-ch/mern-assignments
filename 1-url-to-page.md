# Assignment 1 - What happens between typing a URL and seeing the page?
Example: I type `www.google.com` and press Enter.

1. Browser checks its memory (cache): It checks if it has visited google.com before and saved its address.
2. Finding the address (DNS): If not, it asks a special server for google's address. Computers use number addresses (IP address), not names. It's like looking up a name in a phone book to get the number.
3. Connecting to the server (TCP): The browser connects to google's computer, like making a phone call.
4. Making it secure (TLS/HTTPS): The connection is locked so nobody else can read my data.
5. Asking for the page (HTTP request): The browser says "please send me the page."
6. Server replies (response): Google's server sends back the page's code (HTML) and a message `200 OK`, which means everything is fine.
7. Browser reads the code (DOM): It reads the HTML and understands what is on the page, like text, buttons and images.
8. Downloading the rest: It also downloads the design file (CSS), the action file (JavaScript), images and fonts.
9. Reading the design (CSSOM): It understands the colors, sizes and styles from the CSS.
10. Joining content and design (render tree): It combines what to show with how to show it.
11. Placing things (layout): It decides where each thing goes on the screen.
12. Drawing the page (paint): It shows the final page on my screen.
13. Making it work (JavaScript): The page becomes interactive, like showing suggestions when I type in the search box.