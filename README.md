## Development Env 
I checked and ensured that I have the latest Node.js v16 or higher
I installed Expo CLI using the command: npm install -g expo-cli
Note: I have npm installed
I have VS Code as my IDE for this project

## Create a new project
I created my project with typescript using the following command: npx create-expo-app MyApp

## Run your app
Start the development server using: npx expo start
Scane the QR Code with the expo go app on your mobile phone. I downloaded mine through play store. You may grab yours from apple store if you are using an ios device.
You can also grab the app from expo.dev or use an emulator. I used the expo go app on my mobile phone.

## Challenge
I had a challenge installing Expo CLI due to poor internet connection. I also had a problem signning up on the expo go app for the same reason but once I resolved my internet connection issue, everything worked smoothly.

# 1. Create Your First Mobile App
## Project Setup

1. Navigated to the project directory:
   `cd prodev-mobile-setup`
2. Created a new Expo project:
   `npx create-expo-app@latest .`
3. Edited the Home screen at `app/(tabs)/index.tsx`
   - Changed the default text to **First App Created**
4. Ran the project:
   `npx expo start`

## Reset Observations

Ran `npm run reset-project` and observed:
- I was asked Do you want to move existing files to /app-example instead of deleting them? (Y/n): and I chose y.
- 📁 /app-example directory created.
- ➡️ /app moved to /app-example/app.
- ➡️ /components moved to /app-example/components.
- ➡️ /hooks moved to /app-example/hooks.
- ➡️ /constants moved to /app-example/constants.
- ➡️ /scripts moved to /app-example/scripts.

📁 New /app directory created.
📄 app/index.tsx created.
📄 app/_layout.tsx created.

- Node modules were cleaned.
- App rebuilt from scratch.
