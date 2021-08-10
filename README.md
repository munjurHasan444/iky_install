# iky_install

Follow my step which i have shown below:::<br>
At first make a directory name iky.Then open a terminal in this folder.After that you will follow below's instructions.<br>
 [1] wget http://download.redis.io/redis-stable.tar.gz<br>
 [2] tar xvzf redis-stable.tar.gz<br>
 [3] cd redis-stable<br>
 [4] make<br>
 [5] sudo make install<br>
 [6] git clone https://gitlab.com/kennbroorg/iKy.git<br>
 [7] cd iKy<br>
 [8] sudo apt install python3-pip<br>
 [9] pip3 install -r requirements.txt<br>
 [10] python3 -m pip install -r requirements.txt<br>
 [11] pip3 install python-Levenshtein<br>
 [12] sudo apt update<br>
 [13] sudo apt install nodejs<br>
 [14] sudo apt install npm<br>
 [15] cd frontend<br>
 [16] npm install<br>
 #OPEN A NEW TAB IN THE SAME TERMINAL<br>
 [17]  cd ..<br>
 [18] cd backend<br>
 [19] redis-server<br>
 #OPEN A NEW TAB IN THE SAME TERMINAL<br>
 [20] ./celery.sh<br>
 #OPEN A NEW TAB IN THE SAME TERMINAL<br>
 [21]  python3 app.py <br>
 #OPEN A NEW TAB IN THE SAME TERMINAL<br>
 [22] cd ..<br>
 [23] cd frontend<br>
 [24] npm start<br>
     

When you will run this command [npm install] it will take some time(depend on your internet speed).After that when you will run npm start it will also take some time(may be 10 to 30 minutes).when you se " ｢wdm｣: Compiled successfully", then you will open a new tab on your browser and type http://localhost:4200/

