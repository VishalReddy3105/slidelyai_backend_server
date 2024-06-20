Clone the following GitHub repository to the local machine using the command:
git clone https://github.com/VishalReddy3105/slidelyai_backend_server.git

Then, move the location of the directory where the repository is cloned
cd slidelyai_backend_server

Then, install corresponding dependencies using the following commands in the directory location of the repository:
npm install

npm init -y

npm install express body-parser cors --save

npm install @types/express @types/body-parser @types/cors --save-dev

npm install typescript ts-node nodemon --save-dev

Start the server using the command:
npx ts-node src/index.ts
