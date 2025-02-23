# AI Travel Planner

AI Travel Planner is a smart travel assistant that generates personalized travel itineraries based on user preferences such as budget, number of travelers, travel dates, and preferred destinations. It leverages Gemini AI for intelligent recommendations and integrates with the Amadeus API to provide real-time flight and hotel details.

## Features
- **Personalized Itineraries**: Generates tailored travel plans based on user inputs.
- **Real-time Flight & Hotel Data**: Uses the Amadeus API to fetch up-to-date flight and accommodation details.
- **AI Recommendations**: Powered by Gemini AI to suggest destinations, activities, and accommodations.

## Tech Stack
- **Frontend**: React (Vite)
- **Styling**: Tailwind CSS
- **AI**: Gemini AI
- **APIs**: Amadeus API for flight and hotel data
- **Libraries**: Axios, React-Markdown

## Installation

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/) or npm (Node Package Manager)

### Steps
1. **Clone the Repository**
   ```sh
   git clone https://github.com/HarshwardhanPatil07/Travel-Planner.git
   cd Travel-Planner
   ```

2. **Install Dependencies**
   ```sh
   # Using Yarn
   yarn install
   
   # OR using npm
   npm install
   ```

3. **Set Up Environment Variables**
   Create a `.env` file in the root directory and add the following variables:
   ```ini
   VITE_API_KEY=your-amadeus-api-key
   VITE_API_SECRET=your-amadeus-api-secret
   VITE_GEMINI_KEY=your-gemini-api-key
   ```
   > **Note:** To get API keys:
   > - **Amadeus API Key**: [Sign up here](https://developers.amadeus.com/)
   > - **Gemini API Key**: [Get it here](https://aistudio.google.com/app/apikey)

4. **Run the Development Server**
   ```sh
   # Using Yarn
   yarn dev
   
   # OR using npm
   npm run dev
   ```

## Usage
Once the application is running, users can input their travel preferences, such as:
- Number of travelers
- Budget constraints
- Preferred destinations
- Travel dates

The AI will then generate a comprehensive travel itinerary, including:
- Recommended destinations
- Flight options
- Hotel bookings
- Activity and restaurant suggestions

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any queries, feel free to reach out via GitHub issues.

