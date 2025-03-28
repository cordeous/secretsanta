# Secret Santa Organizer

A modern, simple Secret Santa application built with Next.js, React, and the Perplexity API for AI-powered gift suggestions.

## Features

- Add participants to the Secret Santa exchange
- Set an optional budget for gifts
- Automatically assign Secret Santa pairs
- Generate AI-powered gift suggestions using the Perplexity API
- Modern, responsive UI built with shadcn/ui components

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or later)
- npm or yarn

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/secret-santa-organizer.git
   cd secret-santa-organizer
   ```

2. Install dependencies:
   ```
   npm install
   # or
   yarn install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add your Perplexity API key:
   ```
   PERPLEXITY_API_KEY=your_api_key_here
   ```

## Usage

1. Start the development server:
   ```
   npm run dev
   # or
   yarn dev
   ```

2. Open your browser and navigate to `http://localhost:3000`

3. Use the application:
   - Add participants by entering their names and clicking "Add"
   - Set an optional budget for gifts
   - Click "Assign Secret Santa" to generate assignments and gift suggestions
   - View the assignments and suggestions in the list below

## Project Structure

- `actions.ts`: Server-side actions for assigning Secret Santas and generating gift suggestions
- `secret-santa.tsx`: Main React component for the Secret Santa application
- `README.md`: This file, containing project information and setup instructions

## Dependencies

- Next.js
- React
- shadcn/ui components
- Tailwind CSS
- openai (for Perplexity API integration)
- lucide-react (for icons)
- sonner (for toast notifications)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
