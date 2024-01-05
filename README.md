# SDM

1) make a folder + open cmd first command -> "npm init"(package.json is created)
    i) make public folder --> images folder(put your images)
2) open this folder in vs code 
      npm install express
3) make server.js outside public folder
      check by running node server.js
      test it in your browser
4) make docker file 
      write FROM node:18
	    WORKDIR /app
	    COPY package.json /app
	    RUN npm install
	    COPY . /app
	    CMD node server.js 

5) Now upload this project on github
         i) make new repositary (gitignore--node)
         ii) clone it in your system
         iii) if error oocurs clear proxy and set credential 

    8 commands
    git config --global-unset http.proxy
    git config --global unset https.proxy
    git config --global --unset core.proxy
    git config --global http.proxy http://exam@192.168.10.4:808
    git config --global credential.helper wincred
    git config --global user.name "Pranav Mane"
    git config --global user.email"pranavmane3215@gmail.com"
    git config --global user.password "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"




   
