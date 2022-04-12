## Testing User Stories 
---
- "I want to see book review summaries when i go to the home page of the site."
    - User loads the landing page, and is greated with a welcome hero image, below said image clearly displays all the current book reviews users have submitted.

- "The full book review should show the original user who created the post."
    - When the user expands a book submission on the home page, it clearly displays the full post by a user, with the users name attached.

- "The full book review should show what category/genre the book has been assigned to."
    - Upon opening a book review, it clearly states what category the book has been assigned to. For example, the Dune review is assigned to 'Sci-Fi'.

- "The full book review should show the book name, genre, synopsis, users review, a 'would read again' icon (if users really liked the book) and the user who posted it."
    - When viewing a review, a book title, the category/genre, synopsis of the story and the users personal thoughts/review is all displayed. With some posts having the 'would read again' icon on their posts.

- "I would like to be able to register an account so I can create my own reviews."
    - When greeting to the homepage, the register button on the navbar is displayed. Upon clicking it, I am taken to a register account page where I can create and account. Upon creating the account, I can now share a book to write my own reviews.

- "I would like to be able to log in without issues when I use the correct log in details."
    - I have yet to encounter such issues when logging in with the correct details, the database seems secure and efficient with my login details. 

- "I should not be able to edit or delete a review that is not mine."
    - As a user, I am not able to edit or delete anyone elses posts. Not even as the admin.

- "On the book reviews page, I want to be able to delete or edit my reviews."
    - On the homepage of all book reviews, I can clearly see a edit and delete button on only my own posts.

- "I want the abilty to view my profile."
    - As a user, I have the ability to view my profile, which displays my username, and a share book button which will take me straight to a book review submission page.

- "There should be options to register and login on the site navigation."
    - As a user, there are both options to login and register on the navbar. When logging in, those options are hidden. But a new share book, profile and logout buttons appear.

- "If im logged in i should see navigation options to log out, and view my profile."
    - As a logged in user, upon logging in, there is a log out button displayed. Along side a profile button which will take me to view my profile. Clicking the log out button successfully logs me out of the website.

- "If I encounter an error in rendering a page, I want to know what type of error it is, so I can research on how to solve the problems on my end."
    - As a user, that is on purposely entering my own links or spelling them wrong. I am greeted with a customised error page which displays what error it was, and a button to take me back to the home page thanks to the routes in app.py . In this example, I typed /indexx to recieve a 404 error.

- **Admin** "I want to be able to manage the categories' database with ease, using only the website."
    - As an admin, I am able to see the manage categories button on the navbar, and I can add, edit or delete categories for users to assign their books to.


## Validation
---
All form validation is handled by PyMongo & Flask forms.


## Possible exploits

 - If a admin adds a new category themselves through the site. Then proceeds to share a new book, under that new category. But then when they delete only the category, the book review is still there and still assigned the the category that is no longer existing. So the admin will have to remove the post themselves, along side the sategory if wanted.

 As an admin, I have managed a new category called "Remove Category", posted a non-existent book, removed the category on manage categories page. So the book is still there on the home page for the assessors to see!