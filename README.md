### Take Home Starter Code

Thank you for taking the time to interview for Roots! This take home assignment should give you
some idea of the work we do here and allow you to demonstrate your abilities as a developer.

We are not expecting perfection. We want to see how you tackle a new challenge. 

As I mentioned in the interview, we have plenty of work on the Frontend and Backend. So, for this assignment I'd like you to choose a path based on your own interest:
- *80% Frontend / 20% Backend* - Write a simple API endpoint to fetch some data and then really focus on creating a beatiful, interactive, responsive interface. We have many mobile customers, so bonus points if your layout works or adapts to mobile resolution. But more points will be given to the cleanliness and design of the interface. Animations, hover effects, trendy visuals encouraged. 
- *50% Frontend / 50% Backend* - Write a simple, functional UI that is moderately complex. The UI should serve a relatively robust API, allowing for basic CRUD operations and some interesting queries. 
- *20% Frontend / 80% Backend* - You are allowed to implement a backend engineer's UI (i.e. barebones, ugly, but functional). Focus on a complex and interesting API with data processing functions, complex queries, and detailed/useful logging. 

I'd like you to focus on one or two of the below challenges, depending on your preferred work style selected above:
- Map: Implement a map that displays listings markers within the map region. Map markers should be slightly interactive, allowing for favoriting or labeling. This state can be saved in the UI. If possible, implement a simple filter. Let the user search by price or some other qualifier.
- Dashboard: Create a dashboard that shows interesting insights about our listing data or assumable mortgage data

Core principals I am looking for:
- Code organization - How do you organize code within a file, how do you organize files and folder structure?
- Documentation - Are you writing inline comments where necessary to explain complex logic? Are you writing clear and concise function [docstrings](https://stackoverflow.com/questions/34205666/utilizing-docstrings)?
- Creativity - Is your UI creative, sharp, clean, and/or cute? Does your API solve an interesting problem or serve valuable information?
- Error Handling - Are types checked? Optional chaining? Are try/catch blocks implemented in the API?

### Setup

First, make sure you have `pnpm` [installed on your machine](https://pnpm.io/installation) first:
`corepack prepare pnpm@latest --activate`

1. Add environment variables to the .env file
2. Run `source .env` to load the variables
3. Run `pnpm i` to install all packages
4. Run `pnpm dev` to run the app locally
5. Go to `localhost:3000` to see the application

###