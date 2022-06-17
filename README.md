# DoggyMatch

DoggyMatch is an application which objective is to allow the users to see other people's dog and interact with eachother. You can find live version here: [DoggyMatch](https://doggymatch.netlify.app/)

## Table of Contents

* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Setup](#setup)
* [Page and Routes](#[page-and-routes])
* [Features](#features)
* [Test](#test)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
* [License](#license)

## General Information
It seems that nowadays it is really hard to have a playmate or a walking buddy for your doggy. You might be thinking that an obvious choice could be family and friends dogs, but you need to be sure it is a good match. You want the best for your dog. With our app we have a solution to that. We created an app where you can find the perfect match for your buddy. Our app allows your doggy to match with others based on gender or their interests and in the same time will ensure that playdates are fun for all involved.


## Technologies Used
- React.js - version 18.1.0
- Node.js - version 16.15.1
- Express - version 4.18.1
- MongoDB - version 5.0
- Mongoose - version 6.3.2


## Setup

1. Start by cloning the repository.
2. Install the dependencies in both folders:

```
npm install
```

3. Create a .env file in the frontend folder root with the following:

```
REACT_APP_API_URL = http://localhost:5000
```

4. Create a .env file in the backend folder root with the following:

```
MONGO_URI = your mongodb uri
TOKEN_KEY = Thecodeforjwt
REQUEST_URL = http://localhost:3000
```

5. Start the react and node server with:

```
npm start
```

6. React runs at: http://localhost:3000/. Node runs at http://localhost:5000


## Page and Routes

| Page                                                                                                             | Items                                                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Landing page** <br /> <br /> /                                                                                 | <br /> <br /> Start page                                                                                                                               |
| **Login, signup, profile** <br /> <br /> /login <br /> /signup <br /> /profile <br /> /swipe <br /> /chat <br /> | <br /> <br /> <br /> create a user profile <br /> add all details about your doggy <br /> swipe on dogs <br /> place you can see and chat with matches |

## Features

### Create doggy profile

- You can create a doggy profile after you have an account. You can add all the details about your doggy.

### Matches

- According to your doggy profile we find perfect matches.

### Chating

- You can chat now with your doggy playmate.

## Documentation

- [Prototyping in Figma](https://www.figma.com/file/hEO9VUjNsFZXQOl84DlZQk/DoggyMatch?node-id=0%3A1)
- [Projects GitHub](https://github.com/cimp08/team-2-frontend/projects)
- [Projects GitHub](https://github.com/cimp08/team-2-backend-final/projects)

## Test

- We used Jest for testing to insert, update and delete a dog name.

## Acknowledgements

- This project was inspired by Tinder

## Contact

Created by:

[@RicardoCastelbon](https://github.com/RicardoCastelbon)
[@HeidiDragomir](https://github.com/HeidiDragomir)
[@CemilUlay](https://github.com/cimp08)
[@SaraAbouDabous](https://github.com/sarz2)


## License

Distributed under the [MIT](https://choosealicense.com/licenses/mit/) License.

Feel free to contact us!
