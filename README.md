# mern-app

![](/test.svg)

## description
Simple app which has next features: 
- sign up, sign in, autorization uses jwt tokens through secure http-only cookies without sending authorization header 
- secure routes with rate limits for each route 
- profile page with the list of active sessions and forms to modify your personal data and password 
- user list page and certain user page with its own posts 
- home page which shows all posts (with fetching more on scroll) and has button to submit a new post 
- posts have got like feature (also it shows users who liked a post) 
- forms cover validation for all possible cases and fire notifications
- uploading images and store them on cloudinary

## tech stack
jwt auth, express, mongoose (mongodb), nextjs (react), styled-components, redux, cloudinary