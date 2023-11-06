# PoolStack
PoolStack is a small pool website that displays people who are currently playing a game and people who are waiting to play. The website uses Firebase to achieve real-time updates on the website.

# How to use
1. Log into Firebase.
2. Create a real-time database.
3. Go to "rules" and set read and write to 'true'
4. With the database set up, copy the Firebase config in "Project Settings"
5. In "index.html," change the Firebase config to your own.
6. Open "index.html" in a web browser and type in a name to test if the configuration works.
7. If a name is successfully added, your Firebase has been set up correctly.

# Possible Issues
- If no name appears when joining the queue, please make sure the Firebase config is set up correctly.
- If the config is set correctly, ensure the rules are configured to read and write.
- Constantly check the database to see if it's receiving user inputs. 
