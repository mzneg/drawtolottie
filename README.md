# Lottie Drawing App

Draw anything with your mouse, finger, Apple Pencil, or drawing tablet and export it as an animated Lottie file ready for Framer and other platforms.

## Features

- Pressure-sensitive drawing (Apple Pencil and drawing tablet support)
- Real-time pressure indicator
- Adjustable stroke color and width
- Animation speed control
- Replay your drawing
- Export as Lottie JSON file
- Live preview of your animation

## Deploy to Vercel

### Option 1: Deploy with Vercel CLI

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Navigate to this directory and run:
```bash
vercel
```

3. Follow the prompts to deploy

### Option 2: Deploy via Vercel Dashboard

1. Push this project to a Git repository (GitHub, GitLab, or Bitbucket)
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your repository
5. Vercel will auto-detect the settings
6. Click "Deploy"

### Option 3: Deploy with Vercel GitHub Integration

1. Push this folder to GitHub
2. Connect your GitHub account to Vercel
3. Import the repository
4. Deploy automatically on every push

## Local Development

To run locally:

```bash
npx serve .
```

Then open your browser to `http://localhost:3000`

## How to Use

1. Draw on the canvas with your mouse, finger, or stylus
2. Adjust color, width, and speed settings as needed
3. Click "Replay Animation" to preview
4. Click "Export Lottie JSON" to download
5. Upload the JSON file to Framer or any Lottie-compatible platform

## Using in Framer

1. Export your drawing as a Lottie JSON file
2. In Framer, insert a Lottie component
3. Upload your JSON file
4. The animation will play automatically

## Tech Stack

- Pure HTML, CSS, JavaScript
- Lottie Web for playback
- Canvas API for drawing
- Pointer Events API for pressure sensitivity

## License

MIT
