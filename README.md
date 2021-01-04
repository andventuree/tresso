# Purpose: 

Built this super simple chrome ext to inject simple css to specific elements on a Trello.com board

# Change log

1.0) Cards can take up more space for visibility + easily edit comment button

- When opening a card, a modal pops up on the DOM. Instead of the narrow modal, it takes up 80% width.
- In this modal, the comments should also take up 80% of the max width as well.
- Both these properties need the !important flag as injected CSS sheets actually get loaded onto DOM before API calls are made to fetch web app html and other assets
- Lastly, the edit button should be easier to press since they're bigger now.

JS files are not needed for this chrome ext. But included anyways so i don't need to look it up.

1.1) Make right sidebar bigger for easily readability. Sets width to 40% so you can see more comments
1.2) Make cards 90% opacity so you can see bg. 100% of hover.
1.3) Make edit and delete buttons on comments bigger and more visible.
1.4) When you hover on a comment, the code html tag will expand to take up 100% height

# How to deploy?

1) Open up `chrome://extensions/`
2) Remove existing ext if you already have it, else, skip this step
3) Just select the directory `Desktop/andrew projects/CSS for Trello Chrome Ext/tresso`
e.g., You don't upload individual files