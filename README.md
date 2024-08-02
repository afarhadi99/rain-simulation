<a href="">
  <img alt="\Rain Sim" src="https://github.com/afarhadi99/rain-simulation/blob/master/public/screenshot.jpg">
</a>

# Simple Rain Sumulations

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). It is a simple website that uses React Three Fiber to display several 3D model and control 3D particles, animations, and interactions.

## Requirements
- Node version 18 or higher [https://nodejs.org/en]
- Visual Studio Code [https://code.visualstudio.com/download]
- Github Desktop [https://github.com/apps/desktop]
- Sketchfab for 3D models [https://sketchfab.com/feed]
- Vercel if you want to deploy the project online [https://vercel.com/]

## Getting Started Locally
1. Fork the project and open it locally using Github Desktop
2. Open your project in Visual Studio Code
3. Open terminal and run the following commands to install dependencies and start the website locally
```bash
npm install
npm run dev
```

## Changing 3D Models

3D models are located in the public folder. You can download 3D models from Sketchfab or any other methods. The recommended format for these models is GLB. You can convert models to GLB using Blender [https://www.blender.org/]. 

The 3D scene is inside of src/components/RainSimulation.tsx component. The scene consists of 2 model located in lines 78 and 115. There are also raindrop partices located in line 53-73.


