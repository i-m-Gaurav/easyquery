# EasyQuery

This web application allows users to upload Excel or CSV files containing their data, and then query the data using simple English phrases. The application utilizes React for the frontend, Node.js for the backend, and Supabase as the database.

## Features

- **File Upload**: Users can upload Excel or CSV files containing their data.
- **Natural Language Query**: Users can enter simple English phrases to query their data, such as "Who are the top 10 high scorers in the last 10 years?"
- **SQL Query Generation**: The application converts the user's natural language query into an SQL query.
- **Database Integration**: The generated SQL query is executed against the Supabase database, where the uploaded file is stored.
- **Data Visualization**: The queried data is displayed in a tabular format on the frontend. Additionally, various graphs and charts are generated using D3.js to provide visual insights into the data.

## Technologies Used

- **Frontend**: React
- **Backend**: Node.js
- **Database**: Supabase
- **Data Visualization**: D3.js

## Installation

1. Clone the repository: `git clone https://github.com/your-username/data-exploration-app.git`
2. Navigate to the project directory: `cd data-exploration-app`
3. Install dependencies for the frontend: `cd client && npm install`
4. Install dependencies for the backend: `cd ../server && npm install`

## Configuration

1. Create a Supabase account and obtain the API keys.
2. Create a `.env` file in the `server` directory and add the following environment variables:

SUPABASE_URL=<your-supabase-url>
SUPABASE_KEY=<your-supabase-key>

## Usage

1. Start the frontend development server: `cd client && npm start`
2. Start the backend server: `cd ../server && npm start`
3. Open your web browser and visit `http://localhost:3000` to access the application.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
