# officehours
LMU office hours app with fire chat

**USER AUTHENTICATION**
Authentication takes place with Firebase.
https://www.firebase.com/docs/web/guide/user-auth.html

See working demo here: http://jsfiddle.net/firebase/a221m6pb/embedded/result,js/
See Fiddle here: http://jsfiddle.net/firebase/a221m6pb/light/

**WEB MESSAGING SERVICE**
Amipal utilizes Firebase's own FireChat messaging service. 
github: https://github.com/firebase/firechat
official documentation: https://firechat.firebaseapp.com/docs/

**Known Issues Needing Resolution:**

FireChat Authentication through Email, using Firebase Login credentials
Invite to private chat
Group Chat
display username (currently, we are displaying email)
Chat Window UI - a long string will break chat window UI (word-wrap set to break-word)