# Meme Generator App

A simple meme generator app built using React.js and the Imgflip API. This app allows users to fetch a random meme from a set of 100 stored memes and customize the top and bottom text.

## Features

- Fetches a random meme image from the Imgflip API.
- `Math.random()` generates a random number which helps to get a random image by clicking the "Get New Meme Image" button.
- Users can modify the top and bottom text as per their requirements.
- Built with React 19 and Node.js 22.

## Technologies Used

- React.js (React 19)
- Node.js (Node.js 22)
- Imgflip API
- useState and useEffect hooks

## Installation

### Prerequisites

Ensure you have the following installed before running the app:

- **Node 22** (Download from [Node.js official site](https://nodejs.org/))
- **npm** (Node Package Manager, comes with Node.js)
- **React 19**

### Steps to Install and Run

1. **Clone the Repository**

   ```sh
   git clone https://github.com/Utkarsh-kamra/Meme-Generator.git
   cd meme-generator-app
   ```

2. **Install Dependencies**

   ```sh
   npm install
   ```

3. **Start the Development Server**

   ```sh
   npm run dev
   ```

4. **Open in Browser**\
   The app will be running at:

   ```
   http://localhost:3000
   ```

## Dependencies

Ensure these dependencies are installed:

```json
{
  "dependencies": {
    "react": "^19.0.0",
    "react-dom": "^19.0.0",
    "react-scripts": "^5.0.0"
  }
}
```

## How It Works

1. When the "Get New Meme Image" button is clicked, the app fetches a random meme image from an array of 100 stored memes using the Imgflip API.
2. A random number is generated to pick an image from the array.
3. The user can enter custom text for the top and bottom captions.
4. The final meme is displayed with the selected text.

## Contributing

Feel free to contribute by submitting a pull request!

## License

This project is open-source under the MIT License.

