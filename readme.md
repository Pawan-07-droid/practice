### practice git commonds
jab phele commit krte hai tab error ata hai fir hme ye details fille krni hoti hai

git config --global user.name "Pawan"
git config --global user.email "ps04682050468205@gmail.com"

ab details fill ho chuki hai ab 

commit ho jayega error nhi ayega 

ab iske baad
git branch -M main  
is se humne nhi branch bnai hai 

ab 
git remote add origin https://github.com/Pawan-07-droid/practice

git remote -v  fetch or push ke bare me btata hai


ab apni file ko main ke andr push krenge 

git push origin main

git pull origin main

maine gitignore me venv/ diya 
uske baad app me sub function add kiya then 
git add . 
but venv active nhi hua git status se pata chla
ab maine myenv krke folder banya or uske andr test.py file bnayi or me chata hu ki wo mere github par na jaye to isko git ignore me likh dunga  fir ye isko ignore krega 