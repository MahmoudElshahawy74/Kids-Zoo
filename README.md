Kids Zoo App

Kids Zoo is an interactive and educational app designed to help children learn about animals in a fun and engaging way. The app includes a variety of features such as user authentication, a main view with a matching game, and customizable user settings.

Features

	•	User Authentication: Users can sign up or log in to their accounts. The app stores user credentials using @AppStorage for persistent data storage.
	•	Main View: The main view includes a matching game where kids can match animal images.
	•	Matching Game: An interactive game where users can match pairs of animal images. The game shuffles the animal images every time it is reset.
	•	Settings: Users can log out from the settings menu, which appears as a sheet.

Project Structure

	•	Kids_ZooApp: The main entry point of the app, which determines whether the user should see the login, signup, or main view based on the app’s stored state.
	•	SignUpPage: A sign-up page where new users can create an account.
	•	LoginPage: A login page for existing users to access their accounts.
	•	mainView: The main screen that features the matching game and other interactive elements.
	•	matchedItemView: A custom view that handles the logic and display of the matching game.
	•	mainViewTabBar: A custom tab bar in the main view that includes the user avatar and a settings button.

SwiftUI Practices

	•	State Management: Uses @State for local state management and @AppStorage for persistent state storage across app sessions.
	•	Responsive Layout: Utilizes SwiftUI’s flexible layout system to create a responsive design that adapts to different screen sizes.
	•	Custom Views: Implements reusable custom views for better code organization and separation of concerns.
	•	Async Actions: Uses DispatchQueue.main.asyncAfter to handle timed actions in the game, such as resetting the game after a match.
Demo
https://github.com/user-attachments/assets/77f1e690-7d44-4481-814d-c8acd0187b7a
