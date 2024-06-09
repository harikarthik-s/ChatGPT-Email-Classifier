# ChatGPT Email Classifier

ChatGPT Email Classifier is a web application that allows users to classify their Gmail emails into categories such as Important, Promotions, Social, Marketing, Spam, and General using OpenAI's GPT-3.5 API. Users can sign in with their Google account, fetch their latest emails, and classify them with the power of AI.

## Features

- **Google Sign-In**: Users can sign in using their Google account to access their Gmail emails.
- **Fetch Emails**: Fetch the latest emails from the user's Gmail account.
- **AI Classification**: Classify emails into predefined categories using OpenAI's GPT-3.5 API.
- **Dynamic API Key Input**: Users can input their OpenAI API key to enable AI classification.

## Prerequisites

- Node.js and npm installed on your machine.
- A Google Cloud project set up with OAuth 2.0 credentials.
- An OpenAI API key.

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/chatgpt-email-classifier.git
cd chatgpt-email-classifier
```

### Install Dependencies

```bash
npm install
```

### Set Up Environment Variables

Create a `.env.local` file in the root directory and add the following environment variables:

```
NEXT_PUBLIC_GOOGLE_CLIENT_ID=your-google-client-id
NEXT_PUBLIC_GOOGLE_CLIENT_SECRET=your-google-client-secret
```

Replace `your-google-client-id` and `your-google-client-secret` with your Google OAuth 2.0 credentials.

### Run the Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

## Usage

1. **Enter OpenAI API Key**: Input your OpenAI API key in the provided field.
2. **Sign In with Google**: Click the "Sign in with Google" button to log in using your Google account.
3. **Fetch Emails**: Click the "Fetch Latest Emails" button to fetch the latest emails from your Gmail account.
4. **Classify Emails**: Click the "Classify" button to classify the fetched emails into categories using the OpenAI API.

## Project Structure

- `components/`: Contains the UI components used in the application.
- `pages/`: Contains the Next.js pages, including the main `index.js` file.
- `lib/`: Contains helper functions, such as `getEmails` for fetching emails.
- `public/`: Contains public assets, including images and icons.

## Dependencies

- `next`: React framework for server-side rendering.
- `react`: JavaScript library for building user interfaces.
- `react-dom`: React package for working with the DOM.
- `firebase`: Firebase SDK for authentication.
- `openai`: OpenAI SDK for interacting with GPT-3.5 API.
- `next/image`: Image component for optimized images in Next.js.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

## Acknowledgements

- OpenAI for providing the GPT-3.5 API.
- Google for providing the OAuth 2.0 authentication.
- Next.js for the powerful React framework.
- Firebase for the authentication services.

---

Feel free to reach out with any questions or feedback! Happy coding!
