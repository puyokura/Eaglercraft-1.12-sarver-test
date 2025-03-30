git add .
git commit -m "new"
git push origin main

cd server && java -jar server.jar
java -jar server.jar

cd bungee && java -jar bungee.jar
java -jar bungee.jar