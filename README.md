Link to Bulbasaurus application : https://treyhilson.github.io/bulbasaurus-frontend/

Bulbasaurus API : https://github.com/TreyHilson/bulbasaurus


Wireframe: https://imgur.com/a/pQaoMTz

User --- < Many plants
Plants -- (plant_species, nickname , fact)

## Project Idea
<p>
My idea is a resource for cool house plants. I came up with it brainstorming and going through things like pinterests for inpiration. I think that a lot of people enjoy the idea and practice of adding a piece of nature into their homes. Users would be people who want to begin keeping a log of plants of interest and costs. Perhaps some fun facts about the plant as well.
I also find that in conversations about plants with other people, I always learn something new. That piece was important to me because I wanted certain users to feel like they had something to offer of value as well when adding to their resource.
</p>

# Version 1 User Stories #

<p>As a user I want to be able to sign up with email, pw, pwc.</p>
<p>As a user I want to be able to sign in with email and pw</p>
<p>As a user I want to be able to change password</p>
<p>As a user I want to be able to sign out</p>
<p>As a user I want view all my plants</p>
<p>As a user I want add a new plant planet_species, nickname, and fact</p>
<p>As a user I want edit plant planet_species, nickname, and fact</p>
<p>As a user I want delete plant</p>
Relationships

User has many Plants
Plant belongs to User
Plants Table

plant_species
nickname
fact
user_id
Version 2
Add column to Plant named image_url as string and let user add an image url to their Plant

On front end use image_url as the src for an <img> tag.

Version 3
Let users view a list of All Plants

Backend database: https://bulbasaurus.herokuapp.com/
## Technology Used ##

* Rails
* SQL
* Heroku
