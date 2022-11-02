## TwoTyred
The TwoTyred Application was built as part of the SC2006 Software Engineering Module in Nanyang Technological University.

### About
The TwoTyred Applications serves as an automatic cycling route planner in Singapore.

Create your very own routes by customising your route points, or even try out the I'm Feeling Lucky feature by automically generating a route using the route start point and distance. 

Want to explore routes cycled by other users? Head over to the dashboard page, where you can like ❤️ routes made by other users, or even better, favourite ⭐ routes to add them to your own collection.

Not enough? Our automatic route planner comes with its very own weather, haze (PSI) and temperature querying system which gives you a better idea of what to expect when cycling the route!

Have fun cycling!

### Components

The TwoTyred Application consists of
1. twotyred-frontend (Frontend Interface)
2. twotyred-backend (Backend Server)
3. twotyred-lucky (Backend I'mFeelingLucky Server)

### Deployment
- Frontend: https://swe-fantastic-four.netlify.app/
- Backend: https://swe-backend.chayhuixiang.repl.co/
- Backend-Lucky: https://sqweedy.pythonanywhere.com/ AND https://swe-lucky.chayhuixiang.repl.co/

### Governmental Data/APIs
1. [OneMap API](https://www.onemap.gov.sg/main/v2/)
2. [Data.gov Weather Forecast](https://data.gov.sg/dataset/weather-forecast)
3. [Data.gov Weather API](https://data.gov.sg/dataset/realtime-weather-readings)
4. [Data.gov PSI API](https://data.gov.sg/dataset/psi)

### Class Diagram Implementations
Class | Implementation
|:--------:|:--------:|
Application Backend System | [twotyred-backend/server.js](twotyred-backend/server.js)
Route Planning System | [twotyred-backend/server.js](twotyred-backend/server.js)
Route Factory | [twotyred-backend/server.js](twotyred-backend/server.js)
Environmental Factors Facade | [twotyred-backend/server.js](twotyred-backend/server.js)
Route Information | [twotyred-backend/server.js](twotyred-backend/server.js)
Password Reset | [twotyred-frontend/src/views/login/ResetCard.jsx](twotyred-frontend/src/views/login/ResetCard.jsx)
Log In | [twotyred-frontend/src/views/login/SignInCard.jsx](frontend/src/views/login/SignInCard.jsx)
Sign Up | [twotyred-frontend/src/views/login/RegistrationCard.jsx](twotyred-frontend/src/views/login/RegistrationCard.jsx)
Route Card | [twotyred-frontend/src/components/RouteCard.jsx](twotyred-frontend/src/components/RouteCard.jsx)
Route Card Set | [twotyred-frontend/src/views/dashboard/Dashboard.jsx](twotyred-frontend/src/views/dashboard/Dashboard.jsx)
Dashboard | [twotyred-frontend/src/views/dashboard/Dashboard.jsx](twotyred-frontend/src/views/dashboard/Dashboard.jsx)
User Profile | [twotyred-frontend/src/views/profile/Profile.jsx](twotyred-frontend/src/views/profile/Profile.jsx)
Default Route Planning Page | [twotyred-frontend/src/views/createroute/RouteSelection.jsx](twotyred-frontend/src/views/createroute/RouteSelection.jsx)
I'mFeelingLucky Page | [twotyred-frontend/src/views/createroute/RouteSelection.jsx](twotyred-frontend/src/views/createroute/RouteSelection.jsx)
Route Description Page | [twotyred-frontend/src/views/createroute//RouteDescription.jsx](twotyred-frontend/src/views/createroute//RouteDescription.jsx)

### Tech Stack
- twotyred-frontend
1. [ReactJS](https://reactjs.org/)
2. [TailwindCSS](https://tailwindcss.com/)
3. [Framer Motion](https://www.framer.com/motion/)
4. [HeadlessUI](https://headlessui.com/)
5. [Flowbite](https://flowbite-react.com/)
6. [Heroicons](https://heroicons.com/)
7. [Firebase](https://firebase.google.com/)

- twotyred-backend
1. [Express](https://expressjs.com/)
2. [Firebase](https://firebase.google.com/)

- twotyred-lucky
1. [Flask](https://flask.palletsprojects.com/en/2.2.x/)
2. [OSMnx](https://osmnx.readthedocs.io/en/stable/)
3. [NetworkX](https://networkx.org/)

### Credits
- [Chang Dao Zheng](https://github.com/changdaozheng) (Group Leader)
- [Chay Hui Xiang](https://github.com/chayhuixiang) (Vice Leader)
- [Ang Kai Jun](https://github.com/kaijun123)
- [Evonne Ng](https://github.com/evonneng05)
- [Ivan Loke](https://github.com/IvanLoke)
- [Liu Liwen](https://github.com/liul4)
