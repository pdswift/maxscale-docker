# dodker-compose
# Installation instructions for docker compose on Linux

# this command downloads a binary file from github
step 1: type sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose into a termenle and press enter

# this command applies the executable permission to the binary file downloaded from github 
step 2: type sudo chmod +x /usr/local/bin/docker-compose into a termenle and press enter

# this command checks if docker compose is installed by printing the version to the console
step 4: type docker-compose --version into a termenle and press enter
