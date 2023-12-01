## Capstone Outline --- Registration, Lottery and Winner Notification Application

### by Kim Robinson

My vision of the OMS Field Trips Application was inspired by my past three years as the volunteer trip coordinator for the Oregon Mycological Society (www.wildmushrooms.org).

This project would be a front-end application that will take input from multiple users (about 100) and deliver a result status (chosen/waitlist/not chosen) to user at a specific date.  It will also generate a list of chosen users ('lottery winners') for trip (with contact info) and provide that list to the designated trip leader.
The application will save user input so future trip applications can affect their status and weight the lottery (less likely if have been on previous trip, more likely to be chosen if registered before and wasn't chosen).
Ideally the application will email the applicants with their status and generate a contact list for chosen & waitlisted applicants to be sent to the trip leader.

I think MySQL (or MongoDB) could be a good fit for the database.  For the server side language, I would like to try to use Python (or node.js).  The web framework suggested to work with Python is Flask (or express for node.js).  The UI will be built using Html, CSS and Javascript (and maybe Bootstrap).  The email service to be integrated into the server-side logic will be SMTP Service.  I am unsure if I need to consider security in terms of hashing and SSL at this point.  The concept of ORM (Object-relational mapping) is new to me, but in the goal to keep all the information together here, the recommended ORM for Python is SQLAlchemy and node.js is Sequelize.