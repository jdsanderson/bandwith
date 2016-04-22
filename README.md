Description:
Bandwidth is an app that allows musicians to search out and find like-minded people to make music with. Users will be able to create a personalized profile, complete with the instrument and style they want to play. Using this information, the application will match the user with other musicians that have similar musical interests and fill the roles the needed to make a band. If the user wants to branch out from their comfort zone and try something new, they will be able to include that in their profile and can be matched to anyone.

User Stories:
1. As a user
I want to see a sign-in page
So that I can log in to my account or sign up for one

Acceptance Criteria:
I can only use the functionality of the app if I sign in
I must provide a username and password to sign in
I must provide a potential username, email, and password to make an account
If I do not fill in the required information, I'm presented with errors
After I have successfully signed in, I am redirected to the musician index page

2. As a user
I want to see a musician index page
So that I can see other musicians around me that I'm matched with

Acceptance Criteria:
I should only be able to see musician profiles that I'm matched with
I should see musician names as links that take me to a profile page for that musician
I should see musicians' avatar pics next to their names if they have one

3. As a user
I want to have a profile page
So that I can include the necessary info to match with other artists

Acceptance Criteria:
I must provide my name, email, instrument(s), location, and genre preferences
If I don't provide the required info I will get an error message and my profile won't be updated/created
I can use a picture for an avatar if I wish to
When I'm finished editing/creating my profile, I'm redirected to a musician index page

4. As a user
I want to see another musician's profile page
So that I can get more relevant information on that user

Acceptance Criteria:
I should see the name, email, instrument(s), location, and genre preferences of the other user
I should see the avatar pic of the other user
I should be able to email the other user on their given address in order to connect

5. As a user
I want to be able to search the database
So that I can find specific musicians on the app

Acceptance Criteria:
I should be able to search the database to find specific musicians, bands/genres they are interested in, the instrument they play, or by location
If I do not enter anything into the search bar, nothing will happen
If the item I am searching for doesn't exist, I will find no matches





##TODO:

###Finish Readme

```
/users/sign_up
/users/sign_out
/users/sign_in
```
<p>
^ will work out of the box. You need to configure your github keys for its
link on the sign in page to work. Adding different oauth providers
is just a few lines.
</p>
<p>
Right now this has github oauth added to it. Take a look in
config/initializers/devise.rb for where to add more. You will need
their oauth gem as well. Ex: gem 'omniauth-github'
</p>
# bandwith
