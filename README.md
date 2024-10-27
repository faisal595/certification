Backend 
1.
Clone the repository:git clone https://github.com/yourusername/certificate_generator.git
  cd certificate_generator/server

2.
Install dependencies: npm install OR yarn

3.
Configure environment variables: Create a .env file in the server directory with the following variables:

MONGODB_URI=<your_mongodb_uri>

GOOGLE_CLIENT_EMAIL=<your_google_client_email>

GOOGLE_PRIVATE_KEY=<your_google_private_key>

GOOGLE_DRIVE_FOLDER_ID=<your_google_drive_folder_id>

CERTIFICATE_TEMPLATE_URL=<your_certificate_template_url>
PORT=<PORT_NO>

4.
Start the server: npm start OR yarn start

Frontend Setup


1.
Navigate to the client directory: cd ../client

2.
Install dependencies: npm install OR yarn

3.
Create a .env file in the client directory with the following variable(s):

BASE_URL=<your_base_url>

4.
Start the development server: npm run dev OR yarn dev
