### This is a Note Making application for mobile

## FRONTEND
The frontend has been built in React Native having CRUD operations- Create, Read, Update, and Delete along with a search bar that is connected to the MediaWiki API key to
fetch information about basic keywords from its database. 

## BACKEND
The backend is written in Python using PyCharm and has a text summarization model to it where we send information of a keyword from MediaWiki API and it summarizes
the fetched text 

## INTEGRATION
The integration of frontend and backend is using FastAPI where the user searches a keyword in the  search bar and if it is MediaWiki database, the API call goes to the 
backend Text Summarization model which summarizes the information and then the summarized information is displayed in the application. 
