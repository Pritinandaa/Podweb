# Podweb
======================================
          PodWeb
======================================

Project Overview:
-----------------
Landing Page: The initial page users see, featuring highlights of podcasts, games, courses, and shopping categories. Designed to engage users and direct them to the various features of the application.

Podcast Player: A section dedicated to streaming and managing podcasts. Users can browse through a catalog of podcasts, listen to episodes, and subscribe to their favorites.

Games: A selection of interactive games available for users to play. This component provides entertainment and engagement within the application.

Courses: Users can explore and purchase various courses. The course section includes detailed information about each course, including descriptions, pricing, and instructor details.

Shopping: An e-commerce component where users can browse products, add them to their cart, and proceed with purchases. Features include product descriptions, images, and secure checkout.

Notifications Page:  for real-time notifications. Users receive updates about new content, purchases, or other relevant information.

Setup Instructions:
-------------------
	
1. Import the Database:
   ---------------------
   - Open your MySQL or compatible database management tool.
   - Import the `podcast.sql` file into the `podcast` schema.

   Example Command:
   mysql -u root -p podcast < path/to/podcast.sql

2. Check Database Connection:
   ---------------------------
   - Navigate to `src -> com` directory.
   - Open the `ejdbc.java`and 'loginmac.java' ,'signupcomposer.java','hib.cfg.xml' file.
   - Ensure the database username and password are correct.

   Example:
   private static final String DB_URL = "jdbc:mysql://localhost:3306/podcast";
   private static final String USER = "your_username";
   private static final String PASS = "your_password";

3. Deploy the Project:
   --------------------
   - Open your Integrated Development Environment (IDE).
   - Load the Nexus Technology project.
   - Ensure the server settings are correctly configured.
   - Deploy the project to your server.
   - Start the server to run the application.

4. Access the Application:
   ------------------------
   - Open your web browser.
   - Enter the following URL to access the application:

   http://localhost:8080/podweb/e.zul



Additional Notes:
-----------------
- Ensure all environment variables and configurations are properly set before running the application.
- If you encounter any issues, refer to the application logs for troubleshooting.
- You can mail for any issue on pritimuktananda@gmail.com

======================================
              END
======================================
