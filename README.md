
# T.O.L. - Thinking Out Loud

This is a social network project called T.O.L. (Thinking Out Loud). It was created as the final project for the Kenzie Academy Brazil course. The platform allows users to share their thoughts publicly, similar to Twitter, with interactive elements where users can post and see thoughts (tweets) in real-time.
## Project Overview

T.O.L. is designed as a social media platform where users can share their thoughts, see posts from others, and interact with them. It includes a text input field for creating new posts (tweets), a dynamic feed that updates with new posts, and a navigation menu.

## Features

- Create New Thoughts (Tweets): Users can write their thoughts and click the "Send - Thought" button to share them with others.
- Dynamic Feed: Displays new posts in real-time with the time of posting.
- User Profile Image: Each user has a profile image displayed next to their posts.
- Hashtags: Users can use hashtags in their posts (e.g., #Excited, #NewBeginnings).
- Interactive Layout: The layout has a responsive design and interactive elements.
## Tech Stack

**HTML**: For structuring the web page and content.
**CSS**: For styling the layout, buttons, and text input fields.
**JavaScript**: For handling user input, creating new posts, and dynamically updating the feed.
## Code Explanation

JavaScript Logic

The JavaScript functionality allows users to create new posts and dynamically update the feed:

1. Creating a Tweet: When the user submits a new tweet, the pegarTweet() function is triggered. It takes the text from the input field and calls the criarTweet() function to process and display the tweet.
2. Dynamic Feed: The listarTemplateTweet() function is responsible for creating the HTML structure for each tweet and appending it to the feed.
3. Current Time: Each tweet includes the current time when it is created, formatted as hours:minutes.
4. Reset Input: After a tweet is posted, the input field is cleared.
## Structure

- index.html: Main HTML file for the T.O.L. social network.
- style.css: Styling for the layout, including the navigation menu, posts, and input field.
- script.js: Contains the logic for creating and displaying tweets, handling form submission, and updating the feed.
## License

This project is for educational purposes and is open to use or modify as needed.
