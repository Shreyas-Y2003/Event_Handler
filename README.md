# Event_Handler


Instructions to set up and run the project:

Frontend (React):
Prerequisites:
Node.js and npm (or yarn) installed.
Steps:
1.Clone the repository: git clone <repository_url>
2.Navigate to the frontend directory (usually client or frontend).
3.Install dependencies: npm install (or yarn install)
4.Start the development server: npm start (or yarn start)
--------------------------------------------------------------------------------------------------------
Backend (Node.js):
Prerequisites:
Node.js and npm (or yarn) installed.
Steps:
1.Navigate to the backend directory (usually server or backend).
2.Install dependencies: npm install (or yarn install)
3.Create a .env file in the backend directory and add the following environment variables:
  SUPABASE_URL (from your Supabase project settings)
  SUPABASE_ANON_KEY (from your Supabase project settings)
4.Start the server: npm start (or yarn start)
------------------------------------------------------------------------------------------------------------
Database (Supabase):
Prerequisites:
A Supabase account.
Steps:
  1.Create a new project in Supabase.
  2.Set up the required database tables (e.g., events table with columns for title, description, date, time, etc.).

--------------------------------------------------------------------------------------------------------------------
  Details of the APIs developed:

API Endpoints:
/events:
   GET: Retrieve a list of all events.
   POST: Create a new event.
/events/:id:
   GET: Retrieve a specific event by ID.
   PUT: Update an existing event.
   DELETE: Delete an event.
