# PersonalSite
A personal website designed to showcase the professional portfolio and achievements of an individual.
## Idea
Develop a personal website where visitors can explore the creator's portfolio, interests, and more.
# Technological stack
- Django
- SQLite
- Sessions
- HTML/CSS
# Description:
- Show a main page<br>
GET /<br>
- Retrieve all blog posts<br>
GET /posts<br>
- Retrieve a single blog post and all its comments<br>
GET posts/{slug}<br>
- Comment on the post<br>
POST posts/{slug}<br>
{<br>
&nbsp;&nbsp;&nbsp;"user_name": "Name",<br>
&nbsp;&nbsp;&nbsp;"user_email": "username@gmail.com",<br>
&nbsp;&nbsp;&nbsp;"text": "comment"<br>
}<br>
- Retrieve posts that were saved for later by the user<br>
GET /read-later<br>
- Add or remove posts from the list of saved posts<br>
POST /read-later<br>
# Future plans:
- Implementing user authentication
- Integrating social media sharing
- Implementing a newsletter subscription feature
## Developer
Sviatoslav Baranetskyi

Email: svyatoslav.baranetskiy738@gmail.com
