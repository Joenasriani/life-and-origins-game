LIFE AND ORIGINS

​DESCRIPTION

​Life and Origins is a premium, high-resolution alchemy engine built for the modern web. Unlike traditional alchemy games that rely on static icons, this project utilizes real-time AI image generation via the Imagen 4.0 model to manifest hyper-realistic 3D visuals for every discovery. The experience is designed to be tactile, cinematic, and mobile-first, providing a smooth evolution from basic elements to complex life forms.

​CORE FEATURES

​High Resolution Manifestations: Every new element discovery triggers an AI request to generate a unique, cinematic 3D macro render.
​Procedural Audio Engine: Uses the Web Audio API to synthesize organic sound effects, including resonant plucks for spawning and harmonic chimes for merging.
​Haptic Feedback: Integrated vibration for mobile devices (10ms light pulse) providing a physical confirmation of new discoveries.
​Mobile First Architecture: A dual-pane layout featuring a slim left-hand margin for the element library and a vast right-hand workspace for experimentation.
​Glassmorphism UI: A sleek, dark-themed interface with deep depth, blur effects, and radial gradients for a premium aesthetic.
​
TECH STACK

​Frontend: React 18
​Styling: Tailwind CSS
​Icons: Custom SVG implementations
​AI: Imagen 4.0 (predict endpoint)
​Audio: Web Audio API (procedural synthesis)
​Feedback: Navigator Vibrate API
​
HOW TO PLAY

​Select an element from the left-hand library to manifest it into the void.
​Drag and drop elements on the stage using your mouse or touchscreen.
​Bring two elements close together; a proximity halo will signal they are ready to merge.
​Release the element to trigger the transmutation and discover a new origin.
​Use the void button at the bottom to clear your workspace when needed.

​SETUP INSTRUCTIONS

​This project is delivered as a single-file application. To run it locally:
​Open the life_origins.html file in any modern web browser.
​Ensure you have an active internet connection to load the React and Tailwind CDNs.
​For mobile play, the layout automatically adjusts to provide the vertical sidebar and touch-optimized dragging.
​
AI VISUAL MANIFESTATION

​The game uses specific prompts designed for octane-style 3D renders. Every time a combination like Water plus Fire is made, the system requests a high-resolution image of Steam. The system includes exponential backoff for API calls to ensure a reliable experience even under heavy loads.
​LICENSE

​Proprietary build for the Life and Origins project environment.
