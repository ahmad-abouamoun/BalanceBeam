<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

Balance Beam is a website and mobile app designed to guide users toward a healthier lifestyle by personalizing their physical and mental well-being journey. It offers tailored food recommendations, curated training programs, and interactive fitness tracking, with 3D models to visualize muscle activity. The app also features an AI-powered therapist for emotional support and the ability to book online consultations with nutritionists, fitness coaches, or therapists, providing personalized care. Balance Beam aims to harmonize physical and mental wellness, making it accessible and engaging for all.
### User Stories
#### User
- As a user, I want to input my dietary preferences and health data, so that I can check whether specific ingredients are healthy for me based on the information I provided.
- As a fitness enthusiast, I want to view a 3D model of my body after a workout, so that I can see which muscles I targeted and how intensely they were engaged.

- As a user seeking professional advice, I want to schedule an online meeting with a nutritionist, coach, or therapist, so that I can receive personalized guidance to improve my health and well-being.

#### Nutritionist
- As a nutritionist, I want to analyze a user's dietary habits and provide personalized meal plans, so that I can guide them towards healthier food choices that complement their fitness goals.
- As a nutritionist, I want to track my clients' progress and adjust their meal plans based on their feedback and results, so that I can ensure they continue to make progress toward their goals.
- As a nutritionist, I want to schedule and conduct online consultations with users, so that I can provide real-time advice and answer their questions related to their diet and nutrition.

#### Coach
- As a coach, I want to create workouts for each muscle for my clients, so that I can help them achieve their fitness goals.
- As a coach, I want to communicate directly with my clients through video calls, so that I can offer guidance, motivation, and real-time feedback.
- As a coach, I want the users to be able to see how much they targeted each muscle through a 3D model which will give them some guidance outside the online sessions

#### Therapist
- As a therapist, I want to provide emotional support through an AI-powered system, so that users can receive guidance and therapy whenever they need it, even outside of scheduled sessions.
- As a therapist, I want to schedule and conduct video sessions with users, so that I can provide personalized therapy sessions and help them address their mental health concerns.
- As a therapist, I want to monitor the mental health status of my clients through feedback and session notes, so that I can offer tailored support and advice during our consultations.

Admin 
- As an admin, I want to manage user access levels (e.g., blocking or suspending users), so that I can ensure the security of the platform and address any behavior violations.
- As an admin, I want to be able to create accounts for therapists, nutritionists, and coaches and delete them whenever one is terminated.
- As an admin, I want to see how many users do we many users do we currently have in our website
<br><br>
<!-- Tech stack -->
<img src="./readme/title3.svg"/>

###  BalanceBeam is built using the following technologies:

- This project uses the [React and React Native development frameworks](https://react.dev/). React is a powerful library for building user interfaces on the web, while React Native extends its capabilities to mobile app development. Together, they allow us to use a single codebase for apps across web and mobile platforms.

- For persistent storage (database), the app uses the [MongoDB](https://www.mongodb.com/) package which allows the app to create a custom storage schema and save it to a local database.

- The app uses the font ["Work Sans"](https://fonts.google.com/specimen/Work+Sans) as its main font, and the design of the app adheres to the material design guidelines.

<br><br>
<!-- UI UX -->
<img src="./readme/title4.svg"/>


> We designed BalanceBeam using wireframes and mockups, iterating on the design until we reached the ideal layout for easy navigation and a seamless user experience.

- Project Figma design [figma](https://www.figma.com/design/2MF5oxtEMRFRCJ1vw46BMl/Untitled?node-id=4-182&p=f&t=wkdn3Jb2ReNnnWxl-0)


### Mockups
| Home screen  | Menu Screen | Order Screen |
| ---| ---| ---|
| ![Landing](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) |

<br><br>

<!-- Database Design -->
<img src="./readme/title5.svg"/>

###  Architecting Data Excellence: Innovative Database Design Strategies:

- Insert ER Diagram here


<br><br>


<!-- Implementation -->
<img src="./readme/title6.svg"/>


### User Screens (Mobile)
| Login screen  | Register screen | Landing screen | Loading screen |
| ---| ---| ---| ---|
| ![Landing](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) |
| Home screen  | Menu Screen | Order Screen | Checkout Screen |
| ![Landing](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) |

### Admin Screens (Web)
| Login screen  | Register screen |  Landing screen |
| ---| ---| ---|
| ![Landing](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) |
| Home screen  | Menu Screen | Order Screen |
| ![Landing](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) |

<br><br>


<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

###  Mastering AI Interaction: Unveiling the Power of Prompt Engineering:

- This project uses advanced prompt engineering techniques to optimize the interaction with natural language processing models. By skillfully crafting input instructions, we tailor the behavior of the models to achieve precise and efficient language understanding and generation for various tasks and preferences.

<br><br>

<!-- AWS Deployment -->
<img src="./readme/title8.svg"/>

###  Efficient AI Deployment: Unleashing the Potential with AWS Integration:

- This project leverages AWS deployment strategies to seamlessly integrate and deploy natural language processing models. With a focus on scalability, reliability, and performance, we ensure that AI applications powered by these models deliver robust and responsive solutions for diverse use cases.

<br><br>

<!-- Unit Testing -->
<img src="./readme/title9.svg"/>

###  Precision in Development: Harnessing the Power of Unit Testing:

- This project employs rigorous unit testing methodologies to ensure the reliability and accuracy of code components. By systematically evaluating individual units of the software, we guarantee a robust foundation, identifying and addressing potential issues early in the development process.
<br><br>


<!-- How to run -->
<img src="./readme/title10.svg"/>

> To set up BalanceBeam locally, follow these steps:

### Prerequisites


  ```sh
* npm
  npm install npm@latest -g

  ```
  
### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [example](https://example.com)
2. Clone the repo
   git clone [github](https://github.com/ahmad-abouamoun/BalanceBeam)
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

Now, you should be able to run BalanceBeam locally and explore its features.