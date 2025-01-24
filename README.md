# Meme Picker: Pumpkin's Purrfect Meme Picker

This project is a fun web app called "Pumpkin's Purrfect Meme Picker," where users can select their current emotion and receive a matching meme of a cute cat, displayed in a modal popup. You can also filter the memes by animated GIFs.

## Features
- Choose an emotion from a set of radio buttons.
- Select the option to display only animated GIFs.
- Click a button to get a random meme based on the selected emotion.
- View the meme in a modal popup.
- Close the modal popup by clicking the close button or outside the modal.

## Demo

Live demo is coming soon!

## Tech Stack
- HTML
- CSS
- JavaScript (ES6+)
- Data: [catsData](data.js)

## How It Works

### HTML
The structure includes:
- A header with the app title and a small image (pumpkin).
- A main section with:
  - Emotion selection (radio buttons).
  - Option to filter only GIFs.
  - Button to get a meme image.
  - A modal to display the chosen meme image.

### CSS
The styles ensure that the app is both functional and visually appealing, with elements like the modal implemented using Flexbox for proper alignment.

### JavaScript
- **Emotion selection:** Users can pick an emotion, and the app will filter the available cat memes based on that emotion. 
- **GIF toggle:** You can filter the results to show only GIFs by ticking the checkbox.
- **Modal window:** After selecting an emotion and getting an image, the meme will appear inside a modal that can be closed.
  
The app pulls data from the `catsData` array defined in the `data.js` file.

## Getting Started
Install the dependencies and run the project
```
npm install
npm start
```

Head over to https://vitejs.dev/ to learn more about configuring vite
## About Scrimba

At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜
If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉
The Frontend Developer Career Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

- [Our courses](https://scrimba.com/allcourses)
- [The Frontend Career Path](https://scrimba.com/learn/frontend)
- [Become a Scrimba Pro member](https://scrimba.com/pricing)

Happy Coding!