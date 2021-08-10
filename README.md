# iky_install

Follow my step which i have shown below:::<\br>
At first make a directory name iky.Then open a terminal in this folder.After that you will follow below's instructions.<\br>
 wget http://download.redis.io/redis-stable.tar.gz<\br>
 tar xvzf redis-stable.tar.gz<\br>
 cd redis-stable<\br>
 make<\br>
 sudo make install<\br>
 git clone https://gitlab.com/kennbroorg/iKy.git<\br>
 cd iKy<\br>
 sudo apt install python3-pip<\br>
 pip3 install -r requirements.txt<\br>
 python3 -m pip install -r requirements.txt<\br>
 pip3 install python-Levenshtein<\br>
 sudo apt update<\br>
 sudo apt install nodejs<\br>
 sudo apt install npm<\br>
 cd frontend<\br>
 npm install<\br>
 #OPEN A NEW TAB IN THE SAME TERMINAL<\br>
 cd ..<\br>
 cd backend<\br>
 redis-server<\br>
 #OPEN A NEW TAB IN THE SAME TERMINAL<\br>
 ./celery.sh<\br>
 #OPEN A NEW TAB IN THE SAME TERMINAL<\br>
 python3 app.py <\br>
 #OPEN A NEW TAB IN THE SAME TERMINAL<\br>
 cd ..<\br>
 cd frontend<\br>
 npm start<\br>
     

When you will run this command [npm install] it will take some time(depend on your internet speed).After that when you will run npm start it will also take some time(may be 10 to 30 minutes).when you se " ｢wdm｣: Compiled successfully", then you will open a new tab on your browser and type http://localhost:4200/

