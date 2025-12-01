Step 1: Create a new user
sudo useradd -m -s /bin/bash devuser1

Step 2: Set password for the user
sudo passwd devuser1

Step 3: Create a group for the dev team
sudo groupadd devteam

Step 4: Add the user to the group
sudo usermod -aG devteam devuser1

Step 5: Verify the user and group
id devuser1
