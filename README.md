# Madison Mapple

**Madison Mapple** is an Android app for UW-Madison students to browse off-campus apartments, view locations on a map, compare pricing, and find prospective roommates.

This mobile application was built using Kotlin, Jetpack Compose, Firebase, Room, and Google Maps.

App Demo: https://youtu.be/S5NkHsRFMbI


## 📌 Overview

Madison Mapple helps students:

- Explore apartment listings in **Madison, WI**
- View apartments on an interactive map
- Find compatible roommates
- Chat with an AI assistant
- Create and manage user profiles
- Authenticate using @wisc.edu email


## ✨ Key Features

- Interactive Apartment Map (Google Maps)
- Apartment Listings & Detailed Views
- Roommate Browsing
- Firebase Authentication (UW email)
- AI Chat Assistant
- User Profile Management
- Local Storage with Room
- Modern UI with Jetpack Compose


## ⚙️ Architecture

- MVVM pattern with **Jetpack Compose** for UI
- Clean separation of UI, data, and domain layers
- Use of **Android Architecture Components** (ViewModel, LiveData)


## 🔌 Integrations

- **Firebase** for authentication and analytics
- **Google Gemini API** for AI-powered chat assistance
- **Google Maps SDK** for location features
- **Retrofit** for REST API communication
- **Room** for local database storage


## ⚡️	Performance

- Use of LazyColumn for efficient list rendering
- Image loading via Coil (with caching(
- Asynchronous data fetching with coroutines


## 🛡️	Security

- **Google Services JSON** for secure API keys
- **Proguard rules** for obfuscation
- **Firebase Authentication** for secure login


## 📦	Dependencies

- AndroidX libraries (Compose, Lifecycle, Navigation)
- Firebase SDKs
- Retrofit, Room, Coil


## 📁 Project Structure (High Level)

```
MadisonMapple/
├── app/
│   ├── src/main/                  # App source code
│   ├── build.gradle.kts           # Configuration
│   └── google-services.json
├── build.gradle.kts
└── README.md
```


## 📑 Project Index

<details open>
	<summary><b><code>MADISONMAPPLE/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/settings.gradle.kts'>settings.gradle.kts</a></b></td>
					<td style='padding: 8px;'>- Defines plugin and dependency repositories for the project, ensuring consistent resolution of Android, Google, and Maven Central artifacts<br>- Establishes repository management policies to streamline dependency fetching and plugin application across the entire codebase, supporting a cohesive build environment for the Android application.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/README.md'>README.md</a></b></td>
					<td style='padding: 8px;'>- Provides an overview of the MadisonMapple project, emphasizing its role as a foundational component for mapping functionalities within the application<br>- It highlights the initial implementation of the map feature, serving as a core element for visualizing spatial data and supporting further development in the project’s architecture.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/gradlew.bat'>gradlew.bat</a></b></td>
					<td style='padding: 8px;'>- Facilitates the initialization and execution of the Gradle build system on Windows environments by setting up necessary environment variables, locating Java, and launching the Gradle wrapper<br>- Ensures consistent build automation across development setups, integrating Java and Gradle configurations seamlessly within the projects architecture.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/build.gradle.kts'>build.gradle.kts</a></b></td>
					<td style='padding: 8px;'>- Defines shared build configurations and plugin dependencies for the entire project, ensuring consistent setup across all modules<br>- Facilitates integration of essential tools such as Android, Kotlin, Google services, and Maps platform secrets, streamlining project setup and maintaining uniformity in build processes within the multi-module architecture.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- app Submodule -->
	<details>
		<summary><b>app</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ app</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/proguard-rules.pro'>proguard-rules.pro</a></b></td>
					<td style='padding: 8px;'>- Defines project-specific ProGuard rules to optimize and obfuscate the Android applications codebase<br>- It guides the build process in preserving essential classes and attributes, ensuring app security, performance, and debugging capabilities while maintaining compatibility with features like WebView JavaScript interfaces<br>- This configuration is integral to maintaining a secure and efficient release build.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/build.gradle.kts'>build.gradle.kts</a></b></td>
					<td style='padding: 8px;'>- Defines the Android applications build configuration, integrating essential plugins, SDK settings, and dependencies for UI, maps, location services, Firebase, Room database, and AI functionalities<br>- It orchestrates the setup for a feature-rich, location-aware mobile app with cloud integration and local data storage, ensuring a cohesive architecture that supports user authentication, real-time data, and AI-driven features.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/google-services.json'>google-services.json</a></b></td>
					<td style='padding: 8px;'>- Defines Firebase project configuration for mobile app integration, enabling authentication, storage, and other Firebase services<br>- Facilitates seamless connection between the Android application and Firebase backend, supporting features like user management and data storage within the overall app architecture<br>- Ensures secure and efficient communication with Firebase infrastructure essential for app functionality.</td>
				</tr>
			</table>
			<!-- src Submodule -->
			<details>
				<summary><b>src</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ app.src</b></code>
					<!-- main Submodule -->
					<details>
						<summary><b>main</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ app.src.main</b></code>
							<table style='width: 100%; border-collapse: collapse;'>
							<thead>
								<tr style='background-color: #f8f9fa;'>
									<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
									<th style='text-align: left; padding: 8px;'>Summary</th>
								</tr>
							</thead>
								<tr style='border-bottom: 1px solid #eee;'>
									<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/AndroidManifest.xml'>AndroidManifest.xml</a></b></td>
									<td style='padding: 8px;'>- Defines essential application permissions and metadata for integrating Google Maps services, establishing foundational configurations for location-based features<br>- Facilitates secure access to location data and map functionalities, supporting the app’s core purpose of providing location-aware experiences within the overall architecture<br>- Ensures proper initialization and launch behavior aligned with the app’s user interface and mapping capabilities.</td>
								</tr>
							</table>
							<!-- java Submodule -->
							<details>
								<summary><b>java</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ app.src.main.java</b></code>
									<!-- com Submodule -->
									<details>
										<summary><b>com</b></summary>
										<blockquote>
											<div class='directory-path' style='padding: 8px 0; color: #666;'>
												<code><b>⦿ app.src.main.java.com</b></code>
											<!-- cs407 Submodule -->
											<details>
												<summary><b>cs407</b></summary>
												<blockquote>
													<div class='directory-path' style='padding: 8px 0; color: #666;'>
														<code><b>⦿ app.src.main.java.com.cs407</b></code>
													<!-- myapplication Submodule -->
													<details>
														<summary><b>myapplication</b></summary>
														<blockquote>
															<div class='directory-path' style='padding: 8px 0; color: #666;'>
																<code><b>⦿ app.src.main.java.com.cs407.myapplication</b></code>
															<table style='width: 100%; border-collapse: collapse;'>
															<thead>
																<tr style='background-color: #f8f9fa;'>
																	<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
																	<th style='text-align: left; padding: 8px;'>Summary</th>
																</tr>
															</thead>
																<tr style='border-bottom: 1px solid #eee;'>
																	<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/MainActivity.kt'>MainActivity.kt</a></b></td>
																	<td style='padding: 8px;'>- Serves as the main entry point for the application, initializing the user interface and setting up core components<br>- It configures the app theme, displays the sliding menu, and preloads apartment data into the local database to ensure seamless access throughout the app<br>- This file orchestrates startup processes, integrating data initialization with UI rendering for a cohesive user experience.</td>
																</tr>
															</table>
															<!-- ui Submodule -->
															<details>
																<summary><b>ui</b></summary>
																<blockquote>
																	<div class='directory-path' style='padding: 8px 0; color: #666;'>
																		<code><b>⦿ app.src.main.java.com.cs407.myapplication.ui</b></code>
																	<!-- roommates Submodule -->
																	<details>
																		<summary><b>roommates</b></summary>
																		<blockquote>
																			<div class='directory-path' style='padding: 8px 0; color: #666;'>
																				<code><b>⦿ app.src.main.java.com.cs407.myapplication.ui.roommates</b></code>
																			<table style='width: 100%; border-collapse: collapse;'>
																			<thead>
																				<tr style='background-color: #f8f9fa;'>
																					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
																					<th style='text-align: left; padding: 8px;'>Summary</th>
																				</tr>
																			</thead>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/roommates/RoommateViewModel.kt'>RoommateViewModel.kt</a></b></td>
																					<td style='padding: 8px;'>- Manages the state and interactions for displaying and favoriting roommate profiles within the application<br>- Facilitates data loading, filtering, and toggling favorites, ensuring real-time UI updates and handling asynchronous operations<br>- Integrates with repositories and authentication to provide a seamless experience for browsing and managing roommate information in the apps architecture.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/roommates/RoommateBrowseScreen.kt'>RoommateBrowseScreen.kt</a></b></td>
																					<td style='padding: 8px;'>- Provides the main user interface for browsing and managing roommate profiles within the application<br>- Facilitates profile exploration, filtering between all profiles and favorites, and displays detailed profile information including interests, lifestyle, and contact details<br>- Serves as a central component for user interaction in the roommate matching feature, integrating profile presentation with user preferences and actions.</td>
																				</tr>
																			</table>
																		</blockquote>
																	</details>
																	<!-- chat Submodule -->
																	<details>
																		<summary><b>chat</b></summary>
																		<blockquote>
																			<div class='directory-path' style='padding: 8px 0; color: #666;'>
																				<code><b>⦿ app.src.main.java.com.cs407.myapplication.ui.chat</b></code>
																			<table style='width: 100%; border-collapse: collapse;'>
																			<thead>
																				<tr style='background-color: #f8f9fa;'>
																					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
																					<th style='text-align: left; padding: 8px;'>Summary</th>
																				</tr>
																			</thead>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/chat/ChatViewModel.kt'>ChatViewModel.kt</a></b></td>
																					<td style='padding: 8px;'>- Facilitates real-time chat interactions with an AI-powered model by managing message state and communication flow<br>- It initializes a conversational context, handles user inputs, and updates the UI with AI responses, enabling an engaging and dynamic chat experience within the application<br>- This component integrates AI-driven dialogue capabilities into the overall app architecture.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/chat/ChatScreen.kt'>ChatScreen.kt</a></b></td>
																					<td style='padding: 8px;'>- Facilitates real-time user interaction within the chat interface by displaying message exchanges and managing user input<br>- Integrates with the ViewModel to handle message state, enabling seamless communication with the virtual assistant, Fred<br>- Serves as the primary UI component for engaging users in conversational flows, supporting intuitive message display and input handling within the applications architecture.</td>
																				</tr>
																			</table>
																		</blockquote>
																	</details>
																	<!-- auth Submodule -->
																	<details>
																		<summary><b>auth</b></summary>
																		<blockquote>
																			<div class='directory-path' style='padding: 8px 0; color: #666;'>
																				<code><b>⦿ app.src.main.java.com.cs407.myapplication.ui.auth</b></code>
																			<table style='width: 100%; border-collapse: collapse;'>
																			<thead>
																				<tr style='background-color: #f8f9fa;'>
																					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
																					<th style='text-align: left; padding: 8px;'>Summary</th>
																				</tr>
																			</thead>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/auth/SignUpScreen.kt'>SignUpScreen.kt</a></b></td>
																					<td style='padding: 8px;'>- Implements the user registration interface within the application, enabling new users to create accounts using their @wisc.edu email addresses<br>- Facilitates input validation, password visibility toggling, and account creation through Firebase Authentication, while guiding users through verification and navigation flows essential for onboarding and securing user access in the apps authentication architecture.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/auth/AuthManager.kt'>AuthManager.kt</a></b></td>
																					<td style='padding: 8px;'>- Facilitates user authentication management within the application by providing a centralized access point to Firebase Authentication services<br>- It enables seamless integration of authentication functionalities across the app, supporting secure user sign-in, sign-out, and identity verification processes, thereby ensuring consistent and reliable user authentication handling within the overall app architecture.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/auth/ValidationUtils.kt'>ValidationUtils.kt</a></b></td>
																					<td style='padding: 8px;'>- Provides utility functions for validating user authentication inputs, including email format, password strength, and specific institutional email requirements<br>- These functions support the authentication flow by ensuring user credentials meet necessary criteria, thereby enhancing security and data integrity within the applications user registration and login processes.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/auth/LoginScreen.kt'>LoginScreen.kt</a></b></td>
																					<td style='padding: 8px;'>- Implements the user authentication interface, enabling users to log in with their @wisc.edu email addresses, reset passwords, and navigate to registration<br>- It manages input validation, visual feedback, and interaction with backend authentication services, integrating seamlessly into the apps architecture to facilitate secure user access and account recovery within the overall user management flow.</td>
																				</tr>
																			</table>
																		</blockquote>
																	</details>
																	<!-- profile Submodule -->
																	<details>
																		<summary><b>profile</b></summary>
																		<blockquote>
																			<div class='directory-path' style='padding: 8px 0; color: #666;'>
																				<code><b>⦿ app.src.main.java.com.cs407.myapplication.ui.profile</b></code>
																			<table style='width: 100%; border-collapse: collapse;'>
																			<thead>
																				<tr style='background-color: #f8f9fa;'>
																					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
																					<th style='text-align: left; padding: 8px;'>Summary</th>
																				</tr>
																			</thead>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/profile/UserProfile.kt'>UserProfile.kt</a></b></td>
																					<td style='padding: 8px;'>- Defines the user profile data model and related enumerations to capture personal preferences, habits, and lifestyle details essential for matching or personalization within the application<br>- Facilitates comprehensive user information management, ensuring profile completeness and supporting features that tailor user experiences based on individual characteristics and preferences.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/profile/ProfileViewModel.kt'>ProfileViewModel.kt</a></b></td>
																					<td style='padding: 8px;'>- Manages user profile data within the application, facilitating profile loading, updates, validation, and persistence to Firestore<br>- Handles user interactions related to profile editing, including saving changes and account deletion, while maintaining UI state consistency<br>- Ensures secure account removal through re-authentication, integrating authentication and database operations seamlessly into the overall app architecture.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/profile/ProfileScreen.kt'>ProfileScreen.kt</a></b></td>
																					<td style='padding: 8px;'>- Provides the user interface for managing and editing user profile information within the application<br>- Facilitates viewing, updating, and deleting account details, including personal info, daily routines, habits, lifestyle, housing preferences, and social links<br>- Integrates user authentication actions such as sign-out and account deletion, ensuring a comprehensive profile management experience aligned with the apps architecture.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/profile/ProfileUIState.kt'>ProfileUIState.kt</a></b></td>
																					<td style='padding: 8px;'>- Defines the UI state for the user profile management interface, encapsulating loading, saving, and deletion statuses, validation errors, and user-inputted profile details<br>- Serves as the central data model to synchronize user interactions with the profile editing UI, ensuring consistent state representation across the application’s architecture.</td>
																				</tr>
																			</table>
																		</blockquote>
																	</details>
																	<!-- home Submodule -->
																	<details>
																		<summary><b>home</b></summary>
																		<blockquote>
																			<div class='directory-path' style='padding: 8px 0; color: #666;'>
																				<code><b>⦿ app.src.main.java.com.cs407.myapplication.ui.home</b></code>
																			<table style='width: 100%; border-collapse: collapse;'>
																			<thead>
																				<tr style='background-color: #f8f9fa;'>
																					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
																					<th style='text-align: left; padding: 8px;'>Summary</th>
																				</tr>
																			</thead>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/home/MapScreen.kt'>MapScreen.kt</a></b></td>
																					<td style='padding: 8px;'>- Provides an interactive map interface displaying apartment locations in Madison, WI, by fetching data from a local database<br>- Enhances user experience with custom markers featuring apartment details and images, facilitating easy exploration of available apartments<br>- Integrates data retrieval, map rendering, and dynamic marker content to support location-based browsing within the apps architecture.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/home/MapViewModel.kt'>MapViewModel.kt</a></b></td>
																					<td style='padding: 8px;'>- Provides a centralized view model for managing and retrieving apartment data within the home UI, facilitating real-time updates of apartment listings on the map<br>- Integrates local database access to fetch apartment entities, supporting dynamic and responsive map-based features in the application architecture.</td>
																				</tr>
																			</table>
																		</blockquote>
																	</details>
																	<!-- components Submodule -->
																	<details>
																		<summary><b>components</b></summary>
																		<blockquote>
																			<div class='directory-path' style='padding: 8px 0; color: #666;'>
																				<code><b>⦿ app.src.main.java.com.cs407.myapplication.ui.components</b></code>
																			<table style='width: 100%; border-collapse: collapse;'>
																			<thead>
																				<tr style='background-color: #f8f9fa;'>
																					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
																					<th style='text-align: left; padding: 8px;'>Summary</th>
																				</tr>
																			</thead>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/components/SlidingMenu.kt'>SlidingMenu.kt</a></b></td>
																					<td style='padding: 8px;'>- Implements a dynamic sliding navigation menu integrated with the apps core screens, enabling seamless user navigation across authentication, home, chat, profile, and apartment details<br>- Manages drawer state, route transitions, and access control based on login status, ensuring an intuitive user experience within the apps overall architecture.</td>
																				</tr>
																			</table>
																		</blockquote>
																	</details>
																	<!-- theme Submodule -->
																	<details>
																		<summary><b>theme</b></summary>
																		<blockquote>
																			<div class='directory-path' style='padding: 8px 0; color: #666;'>
																				<code><b>⦿ app.src.main.java.com.cs407.myapplication.ui.theme</b></code>
																			<table style='width: 100%; border-collapse: collapse;'>
																			<thead>
																				<tr style='background-color: #f8f9fa;'>
																					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
																					<th style='text-align: left; padding: 8px;'>Summary</th>
																				</tr>
																			</thead>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/theme/Type.kt'>Type.kt</a></b></td>
																					<td style='padding: 8px;'>- Defines the applications global typography styles, establishing consistent font families, sizes, and weights across the user interface<br>- It enhances visual hierarchy and readability by specifying styles for headings, section titles, and body text, thereby supporting a cohesive and polished design within the overall app architecture.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/theme/Theme.kt'>Theme.kt</a></b></td>
																					<td style='padding: 8px;'>- Defines the applications light color scheme and overall visual theme using Material Design 3 standards<br>- Establishes consistent colors, typography, and shapes to ensure a cohesive user interface across the app<br>- Serves as the central styling component, enabling uniform appearance and branding throughout the project’s UI components.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/theme/Color.kt'>Color.kt</a></b></td>
																					<td style='padding: 8px;'>- Defines the color palette for the applications theme, establishing visual consistency and brand identity<br>- It categorizes core brand colors, neutrals, backgrounds, and semantic indicators, supporting cohesive UI design across the app<br>- This setup ensures a unified aesthetic and enhances user experience by maintaining color harmony throughout the codebase.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/theme/Shape.kt'>Shape.kt</a></b></td>
																					<td style='padding: 8px;'>- Defines a cohesive set of shape styles for the applications UI theme, establishing consistent rounded corner radii across various components<br>- These shape configurations contribute to the overall visual identity and user experience by ensuring uniformity and aesthetic harmony within the apps design system.</td>
																				</tr>
																			</table>
																		</blockquote>
																	</details>
																	<!-- apartments Submodule -->
																	<details>
																		<summary><b>apartments</b></summary>
																		<blockquote>
																			<div class='directory-path' style='padding: 8px 0; color: #666;'>
																				<code><b>⦿ app.src.main.java.com.cs407.myapplication.ui.apartments</b></code>
																			<table style='width: 100%; border-collapse: collapse;'>
																			<thead>
																				<tr style='background-color: #f8f9fa;'>
																					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
																					<th style='text-align: left; padding: 8px;'>Summary</th>
																				</tr>
																			</thead>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/apartments/ApartmentDetailScreen.kt'>ApartmentDetailScreen.kt</a></b></td>
																					<td style='padding: 8px;'>- Displays detailed information about a selected apartment, including images, location, utilities, amenities, contact info, and floor plans<br>- Integrates data retrieval from local database, manages user navigation, and presents a comprehensive, scrollable view to enhance user exploration of apartment options within the apps architecture.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/apartments/ApartmentNameMapper.kt'>ApartmentNameMapper.kt</a></b></td>
																					<td style='padding: 8px;'>- Provides a mapping between apartment display names and their corresponding database identifiers, ensuring consistent and user-friendly naming throughout the application<br>- Facilitates seamless translation between user-facing labels and internal data references, supporting clear communication and data integrity within the apps architecture<br>- This component enhances maintainability by centralizing name conversions for apartment entities.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/apartments/ApartmentListViewModel.kt'>ApartmentListViewModel.kt</a></b></td>
																					<td style='padding: 8px;'>- Manages the retrieval and presentation of apartment data within the applications architecture<br>- Facilitates loading, sorting, and state management of apartment listings, enabling dynamic updates and user interactions<br>- Serves as a bridge between the data repository and UI, ensuring a responsive and organized display of apartment information based on user-selected sorting preferences.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/apartments/ApartmentDetailViewModel.kt'>ApartmentDetailViewModel.kt</a></b></td>
																					<td style='padding: 8px;'>- Provides a ViewModel for managing detailed apartment data within the application<br>- It orchestrates the retrieval and state management of specific apartment information and associated floor plans, enabling seamless data flow between the repository layer and the UI<br>- This component is essential for presenting comprehensive apartment details in the apps architecture.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/apartments/ApartmentsListScreen.kt'>ApartmentsListScreen.kt</a></b></td>
																					<td style='padding: 8px;'>- Provides a comprehensive user interface for browsing, searching, and sorting a list of apartments within the application<br>- Facilitates dynamic filtering, sorting, and visual presentation of apartment data, enabling users to efficiently explore available options and access detailed information through interactive cards<br>- Integrates with the apps data layer to display real-time updates and maintain a seamless user experience.</td>
																				</tr>
																				<tr style='border-bottom: 1px solid #eee;'>
																					<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/main/java/com/cs407/myapplication/ui/apartments/ApartmentListViewModelFactory.kt'>ApartmentListViewModelFactory.kt</a></b></td>
																					<td style='padding: 8px;'>- Provides a factory for creating instances of the ApartmentListViewModel, enabling dependency injection of the ApartmentRepository<br>- It facilitates seamless ViewModel instantiation within the app’s architecture, ensuring proper lifecycle management and data handling for the apartments feature<br>- This component supports the overall architecture by decoupling ViewModel creation from UI components.</td>
																				</tr>
																			</table>
																		</blockquote>
																	</details>
																</blockquote>
															</details>
														</blockquote>
													</details>
												</blockquote>
											</details>
										</blockquote>
									</details>
								</blockquote>
							</details>
						</blockquote>
					</details>
					<!-- androidTest Submodule -->
					<details>
						<summary><b>androidTest</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ app.src.androidTest</b></code>
							<!-- java Submodule -->
							<details>
								<summary><b>java</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ app.src.androidTest.java</b></code>
									<!-- com Submodule -->
									<details>
										<summary><b>com</b></summary>
										<blockquote>
											<div class='directory-path' style='padding: 8px 0; color: #666;'>
												<code><b>⦿ app.src.androidTest.java.com</b></code>
											<!-- cs407 Submodule -->
											<details>
												<summary><b>cs407</b></summary>
												<blockquote>
													<div class='directory-path' style='padding: 8px 0; color: #666;'>
														<code><b>⦿ app.src.androidTest.java.com.cs407</b></code>
													<!-- myapplication Submodule -->
													<details>
														<summary><b>myapplication</b></summary>
														<blockquote>
															<div class='directory-path' style='padding: 8px 0; color: #666;'>
																<code><b>⦿ app.src.androidTest.java.com.cs407.myapplication</b></code>
															<table style='width: 100%; border-collapse: collapse;'>
															<thead>
																<tr style='background-color: #f8f9fa;'>
																	<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
																	<th style='text-align: left; padding: 8px;'>Summary</th>
																</tr>
															</thead>
																<tr style='border-bottom: 1px solid #eee;'>
																	<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/androidTest/java/com/cs407/myapplication/ExampleInstrumentedTest.kt'>ExampleInstrumentedTest.kt</a></b></td>
																	<td style='padding: 8px;'>- Validate the applications context within the Android environment to ensure correct package configuration<br>- Serves as an essential component for verifying that the apps package name aligns with expectations, supporting overall app integrity and correctness within the testing framework of the project architecture.</td>
																</tr>
															</table>
														</blockquote>
													</details>
												</blockquote>
											</details>
										</blockquote>
									</details>
								</blockquote>
							</details>
						</blockquote>
					</details>
					<!-- test Submodule -->
					<details>
						<summary><b>test</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ app.src.test</b></code>
							<!-- java Submodule -->
							<details>
								<summary><b>java</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ app.src.test.java</b></code>
									<!-- com Submodule -->
									<details>
										<summary><b>com</b></summary>
										<blockquote>
											<div class='directory-path' style='padding: 8px 0; color: #666;'>
												<code><b>⦿ app.src.test.java.com</b></code>
											<!-- cs407 Submodule -->
											<details>
												<summary><b>cs407</b></summary>
												<blockquote>
													<div class='directory-path' style='padding: 8px 0; color: #666;'>
														<code><b>⦿ app.src.test.java.com.cs407</b></code>
													<!-- myapplication Submodule -->
													<details>
														<summary><b>myapplication</b></summary>
														<blockquote>
															<div class='directory-path' style='padding: 8px 0; color: #666;'>
																<code><b>⦿ app.src.test.java.com.cs407.myapplication</b></code>
															<table style='width: 100%; border-collapse: collapse;'>
															<thead>
																<tr style='background-color: #f8f9fa;'>
																	<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
																	<th style='text-align: left; padding: 8px;'>Summary</th>
																</tr>
															</thead>
																<tr style='border-bottom: 1px solid #eee;'>
																	<td style='padding: 8px;'><b><a href='https://github.com/sgnesh123/MadisonMapple/blob/master/app/src/test/java/com/cs407/myapplication/ExampleUnitTest.kt'>ExampleUnitTest.kt</a></b></td>
																	<td style='padding: 8px;'>- Provides a foundational unit test to verify core arithmetic functionality within the application<br>- It ensures that basic computational logic operates correctly, supporting the overall reliability of the codebase<br>- As part of the testing suite, it helps maintain code quality during development and future updates, aligning with the projects emphasis on robust, error-free functionality.</td>
																</tr>
															</table>
														</blockquote>
													</details>
												</blockquote>
											</details>
										</blockquote>
									</details>
								</blockquote>
							</details>
						</blockquote>
					</details>
				</blockquote>
			</details>
		</blockquote>
	</details>
</details>

