<p align="center">
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/react.svg" align="center" width="20%">
</p>
<p align="center"><h1 align="center">NLW REACT NATIVE NEARBY</h1></p>
<p align="center">
	<em>Empowering connections, one market at a time.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/last-commit/maycon8609/nlw-rn-nearby?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/maycon8609/nlw-rn-nearby?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/maycon8609/nlw-rn-nearby?style=default&color=0080ff" alt="repo-language-count">
</p>
<br>

## Table of Contents

- [ Overview](#overview)
- [ Features](#features)
- [ Project Structure](#project-structure)
  - [ Project Index](#project-index)
- [ Getting Started](#getting-started)
  - [ Prerequisites](#prerequisites)
  - [ Installation](#installation)
  - [ Usage](#usage)
  - [ Testing](#testing)
- [ Contributing](#contributing)

---

## Overview

**nlw-rn-nearby** is a cutting-edge open-source project designed to revolutionize how users discover nearby markets and deals. By seamlessly connecting users with local market information and exclusive coupons, this project enhances user experience and promotes community engagement. Ideal for individuals seeking convenient and personalized shopping experiences.

---

## Features

|     |      Feature      | Summary                                                                                                                                                                                                     |
| :-- | :---------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ⚙️  | **Architecture**  | <ul><li>Modular architecture with clear separation of concerns.</li><li>Utilizes TypeScript for type safety and scalability.</li><li>Follows best practices for scalability and maintainability.</li></ul>  |
| 🔩  | **Code Quality**  | <ul><li>Consistent coding style and conventions.</li><li>Well-documented codebase with meaningful variable and function names.</li><li>Utilizes linters and code formatters for code consistency.</li></ul> |
| 📄  | **Documentation** | <ul><li>Comprehensive documentation in TypeScript.</li><li>Includes detailed explanations of project structure and setup.</li><li>API and package configuration documentation available.</li></ul>          |
| 🔌  | **Integrations**  | <ul><li>Integration with Docker for containerization.</li><li>Uses npm for package management.</li><li>Prisma for database schema management.</li></ul>                                                     |
| 🧩  |  **Modularity**   | <ul><li>Highly modular codebase with reusable components.</li><li>Encourages separation of concerns for easier maintenance and testing.</li><li>Follows a component-based architecture.</li></ul>           |
| 🧪  |    **Testing**    | <ul><li>Includes unit tests and integration tests.</li><li>Utilizes npm for running test suites.</li><li>Ensures code reliability and robustness through testing.</li></ul>                                 |
| ⚡️ |  **Performance**  | <ul><li>Optimized code for efficient performance.</li><li>Utilizes best practices for performance tuning.</li><li>Regular performance testing and optimization.</li></ul>                                   |
| 🛡️  |   **Security**    | <ul><li>Follows security best practices.</li><li>Implements secure coding standards.</li><li>Regular security audits and updates.</li></ul>                                                                 |
| 📦  | **Dependencies**  | <ul><li>Uses npm for managing project dependencies.</li><li>Includes a list of project dependencies in package.json.</li><li>Enforces exact version saving for dependencies.</li></ul>                      |

---

## Project Structure

```sh
└── nlw-rn-nearby/
    ├── api
    │   ├── .env
    │   ├── .gitignore
    │   ├── .npmrc
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── prisma
    │   ├── src
    │   └── tsconfig.json
    └── mobile
        ├── .gitignore
        ├── app.json
        ├── assets
        ├── package-lock.json
        ├── package.json
        ├── src
        └── tsconfig.json
```

### Project Index

<details open>
	<summary><b><code>NLW-RN-NEARBY/</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>__root__</b></summary>
		<blockquote>
			<table>
			</table>
		</blockquote>
	</details>
	<details> <!-- api Submodule -->
		<summary><b>api</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/.npmrc'>.npmrc</a></b></td>
				<td>Enforce exact version saving for dependencies in the project's API configuration.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/tsconfig.json'>tsconfig.json</a></b></td>
				<td>- Defines TypeScript compiler options for the project, targeting ES2022 with ES2023 libraries<br>- Maps custom paths to source files and enforces strict typing and consistent casing<br>- Configures module handling for Node.js environment with ES module interoperability.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/package.json'>package.json</a></b></td>
				<td>- Facilitates running and managing API server for the Nearby app<br>- Handles starting the server and database migrations using Knex<br>- Seeds the Prisma database with initial data<br>- Dependencies include Prisma, Express, and Zod<br>- Dev dependencies include TypeScript and related types<br>- Overall, crucial for API functionality and data management in the project architecture.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/package-lock.json'>package-lock.json</a></b></td>
				<td>- The `api/package-lock.json` file in the project structure manages dependencies for the API module, including packages like `@prisma/client`, `express`, and `zod`<br>- It ensures version consistency and stability for the API functionality within the codebase architecture.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/.env'>.env</a></b></td>
				<td>Enables configuration of the database URL for the API.</td>
			</tr>
			</table>
			<details>
				<summary><b>src</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/src/server.ts'>server.ts</a></b></td>
						<td>- The code in `api/src/server.ts` sets up an Express server to handle incoming requests, define routes, and manage errors<br>- It listens on a specified port and logs a message upon successful startup<br>- This file plays a crucial role in initializing the server and orchestrating the flow of incoming requests within the project architecture.</td>
					</tr>
					</table>
					<details>
						<summary><b>middlewares</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/src/middlewares/error-handling.ts'>error-handling.ts</a></b></td>
								<td>- Handles errors in the API by returning appropriate responses based on the type of error encountered<br>- It distinguishes between application errors and validation errors, providing specific messages and status codes accordingly<br>- This middleware ensures consistent error handling throughout the project, enhancing the overall reliability and user experience.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>utils</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/src/utils/AppError.ts'>AppError.ts</a></b></td>
								<td>Defines a reusable class for handling custom error messages and status codes within the project's API.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>controllers</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/src/controllers/markets-controller.ts'>markets-controller.ts</a></b></td>
								<td>- The MarketsController in the api/src/controllers/markets-controller.ts file handles requests related to market data<br>- It retrieves markets based on category or specific IDs and returns the results in a structured format<br>- This controller plays a crucial role in managing market information within the project's architecture.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/src/controllers/categories-controller.ts'>categories-controller.ts</a></b></td>
								<td>- The CategoriesController in the api/src/controllers/categories-controller.ts file retrieves and returns a list of categories in ascending order from the database<br>- This controller plays a crucial role in handling requests related to categories within the project's architecture.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/src/controllers/coupons-controller.ts'>coupons-controller.ts</a></b></td>
								<td>- The CouponsController in the api/src/controllers/coupons-controller.ts file handles coupon updates for a specific market in the project<br>- It validates parameters, decrements available coupons, generates a unique coupon code, and returns it in the response<br>- This controller ensures proper management of coupons within the system.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>routes</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/src/routes/categories-route.ts'>categories-route.ts</a></b></td>
								<td>Expose category routes for handling requests using the CategoriesController to manage category data within the API.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/src/routes/coupons-route.ts'>coupons-route.ts</a></b></td>
								<td>- Enables updating coupons for a specific market within the API by utilizing the CouponsController<br>- The code file defines routes for handling PATCH requests to update coupons based on the market ID<br>- This functionality is crucial for managing and modifying coupon information within the overall project architecture.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/src/routes/index.ts'>index.ts</a></b></td>
								<td>- Defines API routes for categories, markets, and coupons using Express Router<br>- Integrates routes for each entity to enable structured access within the project.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/src/routes/markets-route.ts'>markets-route.ts</a></b></td>
								<td>- Defines routes for market data retrieval based on category and ID, utilizing the MarketsController to handle requests<br>- This file plays a crucial role in structuring the API endpoints for accessing market information within the project architecture.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>database</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/src/database/prisma.ts'>prisma.ts</a></b></td>
								<td>Enables database connectivity and query logging using PrismaClient in the project's API module.</td>
							</tr>
							</table>
						</blockquote>
					</details>
				</blockquote>
			</details>
			<details>
				<summary><b>prisma</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/prisma/seed.ts'>seed.ts</a></b></td>
						<td>- Summary:
The code file `seed.ts` in the `api/prisma` directory is responsible for seeding initial data into the database using Prisma<br>- It populates categories and markets with predefined values like "Alimentação," "Compras," and others<br>- This seeding process ensures that the database starts with essential data for the application to function correctly.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/prisma/schema.prisma'>schema.prisma</a></b></td>
						<td>- Defines Prisma schema for categories, markets, and rules with relationships<br>- Specifies data model structure and database configuration for the project.</td>
					</tr>
					</table>
					<details>
						<summary><b>migrations</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/prisma/migrations/migration_lock.toml:Zone.Identifier'>migration_lock.toml:Zone.Identifier</a></b></td>
								<td>Ensures synchronization and consistency across database migrations in the project.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/prisma/migrations/migration_lock.toml'>migration_lock.toml</a></b></td>
								<td>Ensure version control system tracks the SQLite provider for Prisma migrations in the specified file.</td>
							</tr>
							</table>
							<details>
								<summary><b>20241112181659_create_tables</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/prisma/migrations/20241112181659_create_tables/migration.sql:Zone.Identifier'>migration.sql:Zone.Identifier</a></b></td>
										<td>Improve database schema by defining tables and relationships for the project's data model.</td>
									</tr>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/api/prisma/migrations/20241112181659_create_tables/migration.sql'>migration.sql</a></b></td>
										<td>Define database schema for categories, rules, and markets, establishing relationships between them.</td>
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
	<details> <!-- mobile Submodule -->
		<summary><b>mobile</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/tsconfig.json'>tsconfig.json</a></b></td>
				<td>- Defines TypeScript compiler options for strict type checking and module resolution, extending a base configuration<br>- Maps custom paths to source files for improved code organization<br>- Includes TypeScript and TypeScriptX files for compilation, along with type definitions for Expo environment.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/package.json'>package.json</a></b></td>
				<td>Define project dependencies and scripts for running the mobile app.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/app.json'>app.json</a></b></td>
				<td>- Defines project configuration settings for the mobile app, including name, icon, orientation, and plugins<br>- Specifies platform-specific details for iOS, Android, and web<br>- Enables new architecture features and experiments like typed routes.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/package-lock.json'>package-lock.json</a></b></td>
				<td>- The `package-lock.json` file in the mobile directory of the project manages dependencies for the "nearby" application<br>- It ensures that the correct versions of required packages like "@expo-google-fonts/rubik" and "@react-navigation/native" are installed, maintaining consistency and stability in the project's architecture.</td>
			</tr>
			</table>
			<details>
				<summary><b>src</b></summary>
				<blockquote>
					<details>
						<summary><b>components</b></summary>
						<blockquote>
							<details>
								<summary><b>button</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/button/index.tsx'>index.tsx</a></b></td>
										<td>- The code in the provided file defines a reusable Button component for a mobile application, including features like loading state handling and customizable icons<br>- This component encapsulates touchable behavior and visual styling, enhancing user interaction and visual consistency across the app.</td>
									</tr>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/button/styles.ts'>styles.ts</a></b></td>
										<td>- Define button styles for mobile components using React Native StyleSheet, adhering to the project's theme colors and fonts<br>- The styles ensure consistent design across buttons, setting dimensions, colors, and text properties for a cohesive user interface.</td>
									</tr>
									</table>
								</blockquote>
							</details>
							<details>
								<summary><b>places</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/places/index.tsx'>index.tsx</a></b></td>
										<td>- Enables displaying a list of places with interactive bottom sheet functionality for a mobile app<br>- Utilizes React Native components for smooth user experience<br>- Integrates with Expo Router for seamless navigation<br>- Enhances user engagement by showcasing nearby locations dynamically.</td>
									</tr>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/places/styles.ts'>styles.ts</a></b></td>
										<td>- Define styles for places component in the mobile app using React Native StyleSheet, adhering to the project's theme colors and fonts<br>- The styles include container, content, indicator, and title properties to ensure consistent visual presentation across the app.</td>
									</tr>
									</table>
								</blockquote>
							</details>
							<details>
								<summary><b>market</b></summary>
								<blockquote>
									<details>
										<summary><b>cover</b></summary>
										<blockquote>
											<table>
											<tr>
												<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/market/cover/index.tsx'>index.tsx</a></b></td>
												<td>- Implement a React Native component for displaying a cover image with a back button<br>- The component utilizes an ImageBackground from react-native and an IconArrowLeft from @tabler/icons-react-native<br>- It also integrates with the Expo router for navigation.</td>
											</tr>
											<tr>
												<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/market/cover/styles.ts'>styles.ts</a></b></td>
												<td>- Define styles for the market cover component, ensuring consistent visual presentation across the mobile app<br>- The code file sets dimensions, padding, and background color for the cover container, enhancing the overall user experience.</td>
											</tr>
											</table>
										</blockquote>
									</details>
									<details>
										<summary><b>info</b></summary>
										<blockquote>
											<table>
											<tr>
												<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/market/info/index.tsx'>index.tsx</a></b></td>
												<td>- Defines a reusable component for displaying information in the market section of the mobile app<br>- The component renders an icon and a description text styled according to the theme of the app<br>- This enhances the user experience by providing consistent and visually appealing market information display across the application.</td>
											</tr>
											<tr>
												<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/market/info/styles.ts'>styles.ts</a></b></td>
												<td>Define styles for market information display in the mobile app, ensuring consistent design and layout.</td>
											</tr>
											</table>
										</blockquote>
									</details>
									<details>
										<summary><b>coupon</b></summary>
										<blockquote>
											<table>
											<tr>
												<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/market/coupon/index.tsx'>index.tsx</a></b></td>
												<td>Define a reusable Coupon component that displays a code with an accompanying icon in a visually appealing manner within the mobile application's market section.</td>
											</tr>
											<tr>
												<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/market/coupon/styles.ts'>styles.ts</a></b></td>
												<td>- Define styles for market coupon components, ensuring a consistent look and feel across the mobile app<br>- Set specific visual properties like colors, fonts, and padding to enhance the user experience and maintain brand coherence.</td>
											</tr>
											</table>
										</blockquote>
									</details>
									<details>
										<summary><b>details</b></summary>
										<blockquote>
											<table>
											<tr>
												<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/market/details/index.tsx'>index.tsx</a></b></td>
												<td>- The Details component renders market information including name, description, address, phone, coupons, and rules<br>- It utilizes various icons and styles to present the data in a visually appealing manner<br>- This component plays a crucial role in displaying detailed market information within the mobile application.</td>
											</tr>
											<tr>
												<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/market/details/styles.ts'>styles.ts</a></b></td>
												<td>Define styles for market details component to ensure consistent and visually appealing presentation.</td>
											</tr>
											</table>
										</blockquote>
									</details>
								</blockquote>
							</details>
							<details>
								<summary><b>category</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/category/index.tsx'>index.tsx</a></b></td>
										<td>- Define and render interactive category components with icons and text, allowing for selection and deselection based on user interaction<br>- The components are styled based on the selection state, enhancing the user experience within the mobile application.</td>
									</tr>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/category/styles.ts'>styles.ts</a></b></td>
										<td>- Define styles for category components in the mobile app, specifying layout, colors, and typography<br>- The styles ensure consistent visual presentation across categories, with selected items highlighted in green<br>- This file contributes to maintaining a cohesive design system within the project's architecture.</td>
									</tr>
									</table>
								</blockquote>
							</details>
							<details>
								<summary><b>loading</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/loading/index.tsx'>index.tsx</a></b></td>
										<td>- Implements a loading component using ActivityIndicator from react-native<br>- Displays a loading indicator with a green color scheme, enhancing user experience during data fetching operations.</td>
									</tr>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/loading/styles.ts'>styles.ts</a></b></td>
										<td>- Defines loading screen styles for the mobile app, ensuring a consistent user experience<br>- The code sets up the layout properties like centering content and background color, enhancing visual coherence across the app.</td>
									</tr>
									</table>
								</blockquote>
							</details>
							<details>
								<summary><b>place</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/place/index.tsx'>index.tsx</a></b></td>
										<td>- Define a reusable React component to display place details with an image, name, description, coupons, and address<br>- The component leverages TouchableOpacity for interactivity and styling<br>- It encapsulates the visual representation of a place within the mobile application, promoting code reusability and maintainability.</td>
									</tr>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/place/styles.ts'>styles.ts</a></b></td>
										<td>- Define styles for a mobile place component, ensuring consistent UI across the app<br>- The code sets dimensions, padding, borders, and text styles for the container, image, content, name, description, and footer elements<br>- It leverages predefined colors and fonts for a cohesive design language.</td>
									</tr>
									</table>
								</blockquote>
							</details>
							<details>
								<summary><b>categories</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/categories/index.tsx'>index.tsx</a></b></td>
										<td>- Enables rendering a horizontal list of categories with icons and names<br>- Allows users to select a category by tapping on it<br>- Supports smooth scrolling and visually highlights the selected category.</td>
									</tr>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/categories/styles.ts'>styles.ts</a></b></td>
										<td>- Defines styles for the categories component, ensuring proper layout and spacing<br>- The code sets specific attributes like container height and content padding, enhancing the visual presentation of the component within the mobile application.</td>
									</tr>
									</table>
								</blockquote>
							</details>
							<details>
								<summary><b>welcome</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/welcome/index.tsx'>index.tsx</a></b></td>
										<td>- Defines the Welcome component rendering a logo and welcoming text in a React Native app<br>- It leverages styles for consistent UI across the project, enhancing user experience.</td>
									</tr>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/welcome/styles.ts'>styles.ts</a></b></td>
										<td>- Define styles for the welcome screen components using React Native StyleSheet, adhering to the project's theme colors and fonts<br>- The styles file in mobile/src/components/welcome organizes the layout properties for the logo, title, and subtitle elements, ensuring consistent design across the application.</td>
									</tr>
									</table>
								</blockquote>
							</details>
							<details>
								<summary><b>steps</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/steps/index.tsx'>index.tsx</a></b></td>
										<td>- Illustrating a visual guide to the app's functionality, the Steps component showcases a series of steps with icons and descriptions<br>- It enhances user experience by simplifying complex processes into digestible chunks, aiding users in navigating the app effortlessly.</td>
									</tr>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/steps/styles.ts'>styles.ts</a></b></td>
										<td>Define styles for mobile app components using React Native StyleSheet, adhering to the project's theme colors and font family.</td>
									</tr>
									</table>
								</blockquote>
							</details>
							<details>
								<summary><b>step</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/step/index.tsx'>index.tsx</a></b></td>
										<td>- Defines a reusable Step component for displaying titles, descriptions, and icons in a mobile app<br>- The component leverages React Native elements and custom styles to present structured content to users<br>- This component plays a crucial role in enhancing the user experience by breaking down complex information into digestible steps.</td>
									</tr>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/components/step/styles.ts'>styles.ts</a></b></td>
										<td>- Define styles for step components in the mobile app, ensuring consistent design and layout<br>- The code establishes the visual properties for the step container, title, and description, maintaining a cohesive user interface across the application.</td>
									</tr>
									</table>
								</blockquote>
							</details>
						</blockquote>
					</details>
					<details>
						<summary><b>utils</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/utils/categories-icons.ts'>categories-icons.ts</a></b></td>
								<td>Define category icons for the mobile app using pre-defined icons for different categories.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>services</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/services/api.ts'>api.ts</a></b></td>
								<td>Enables communication with the backend server by creating an instance of Axios with predefined base URL and timeout settings.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>styles</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/styles/theme.ts'>theme.ts</a></b></td>
								<td>Exports color and font family styles for the mobile application, enhancing consistency and maintainability across the codebase architecture.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/styles/font-family.ts'>font-family.ts</a></b></td>
								<td>Define font families for consistent styling across the mobile application.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/styles/colors.ts'>colors.ts</a></b></td>
								<td>- Define color palettes for the mobile app UI to maintain consistency and enhance user experience<br>- The 'colors.ts' file centralizes color definitions for various elements, ensuring a cohesive visual identity across the application.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>app</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/app/index.tsx'>index.tsx</a></b></td>
								<td>- Defines the main app screen layout and navigation flow, showcasing a welcoming message, step indicators, and a call-to-action button<br>- Integrates React Native components for a seamless user experience.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/app/_layout.tsx'>_layout.tsx</a></b></td>
								<td>- Defines the app's main layout structure, ensuring fonts are loaded before rendering<br>- Utilizes Expo and React Native components for smooth navigation and visual consistency.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/app/home.tsx'>home.tsx</a></b></td>
								<td>- Implements a dynamic home screen displaying categorized markets on a map<br>- Fetches categories and markets from an API, allows user location tracking, and enables market selection for detailed information<br>- Displays markers with callouts for each market location<br>- Overall, the code enhances user experience by providing interactive and informative content on the map interface.</td>
							</tr>
							</table>
							<details>
								<summary><b>market</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-rn-nearby/blob/master/mobile/src/app/market/[id].tsx'>[id].tsx</a></b></td>
										<td>- The code file in mobile/src/app/market/[id].tsx fetches market data, displays a cover image, and allows users to scan QR codes to redeem coupons<br>- It handles camera permissions, coupon fetching, and modal interactions<br>- This file plays a crucial role in enhancing user engagement and providing a seamless experience within the market section of the app.</td>
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
</details>

---

## Getting Started

### Prerequisites

Before getting started with nlw-rn-nearby, ensure your runtime environment meets the following requirements:

- **Programming Language:** TypeScript
- **Package Manager:** Npm

### Installation

Install nlw-rn-nearby using one of the following methods:

**Build from source:**

1. Clone the nlw-rn-nearby repository:

```sh
❯ git clone git@github.com:maycon8609/nlw-rn-nearby.git
```

2. Navigate to the project directory:

```sh
❯ cd nlw-rn-nearby
```

3. Install the project dependencies:

**Using `npm`** &nbsp; [<img align="center" src="https://img.shields.io/badge/npm-CB3837.svg?style={badge_style}&logo=npm&logoColor=white" />](https://www.npmjs.com/)

```sh
❯ npm install
```

### Usage

Run nlw-rn-nearby using the following command:
**Using `npm`** &nbsp; [<img align="center" src="https://img.shields.io/badge/npm-CB3837.svg?style={badge_style}&logo=npm&logoColor=white" />](https://www.npmjs.com/)

```sh
❯ npm start
```

### Testing

Run the test suite using the following command:
**Using `npm`** &nbsp; [<img align="center" src="https://img.shields.io/badge/npm-CB3837.svg?style={badge_style}&logo=npm&logoColor=white" />](https://www.npmjs.com/)

```sh
❯ npm test
```

## Contributing

- **💬 [Join the Discussions](https://github.com/maycon8609/nlw-rn-nearby/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/maycon8609/nlw-rn-nearby/issues)**: Submit bugs found or log feature requests for the `nlw-rn-nearby` project.
- **💡 [Submit Pull Requests](https://github.com/maycon8609/nlw-rn-nearby/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git@github.com:maycon8609/nlw-rn-nearby.git
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/maycon8609/nlw-rn-nearby/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=maycon8609/nlw-rn-nearby">
   </a>
</p>
</details>

---
