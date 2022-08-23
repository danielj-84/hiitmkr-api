# <span style="color:orangered">HIITmkr (server) </span>

<!-- Online demo: [SSL CoffeeDir](https://coffee-dir.herokuapp.com) | [No-SSL CoffeeDir](http://www.coffeedir.ca) -->

### Making your HIIT workout more fun and more encouraging!

---

<br />

#### BRAINSTATION WEB DEVELOPMENT BOOTCAMP CAPSTONE PROJECT

_The problem:_
<span> I love the gym - other than behind the keyboard, it’s my happy place. What I don’t particularly enjoy is long drawn out cardio workouts - which is why I’ve gravitated towards HIIT, or high-intensity interval training. With HIIT, you alternate between short intervals of high intensity exercise and low intensity exercise - you basically get the benefits of a long cardio session in a much shorter, albeit more intense, workout. The problem is that current apps often give you a countdown timer and a series of beeps - not too inspiring! I wanted to make an app to improve that experience and so HIITmkr will do just that by using your favourite artists to encourage you!</span>

<br />

<h2 style="color: yellow">Tech stack</h2>

<a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="80" height="80"/> </a>
<a href="https://create-react-app.dev/" target="_blank" rel="noreferrer"> <img src="https://create-react-app.dev/img/logo.svg" alt="create-react-app" width="80" height="80"/> </a>
<a href="https://sass-lang.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="sass" width="80" height="80"/> </a>
<a href="https://axios-http.com/" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/8939680/57233883-20344080-6fe5-11e9-8169-1eeb4c782683.png" alt="Axios" width="160" height="80"/> </a>
<a href="https://reactrouter.com/" target="_blank" rel="noreferrer"> <img src="https://miro.medium.com/max/1400/0*nH627PKQdg4-BCfj" alt="Axios" width="160" height="80"/> </a>
<a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"> <img src="https://nodejs.org/static/images/logos/nodejs-new-pantone-black.svg" alt="NodeJS" width="80" height="80"/> </a>
<a href="https://helmetjs.github.io/" target="_blank" rel="noreferrer"> <img src="https://repository-images.githubusercontent.com/3329923/2fd1c70a-c521-4087-9c1d-bf3e1fff3e4d" alt="helmetJS" width="160" height="80"/> </a>
<a href="https://helmetjs.github.io/" target="_blank" rel="noreferrer"> <img src="https://miro.medium.com/max/1400/1*8ETcaw-gA1dYW4EFxqGK3w.png" alt="expressJS" width="160" height="80"/> </a>

<br/>

<h2 style="color: yellow">Setup the project</h2>

### INSTALLATION NOTES
## In order for HIITmkr to function properly, the client must also be installed: (https://github.com/danielj-84/hiitmkr-client)

## To run HIITmkr, a Spotify Premium account is necessary to obtain a `client id`, `client secret`(rquired by Spotify for authentication) : https://developer.spotify.com/documentation/general/guides/authorization/app-settings/

### Installation (in root directory, use terminal/bash commands)
for both `hiitmkr-client` and `hiitmkr-api` : 
```bash
npm i
```

### Set up `.env` file inside `hiitmkr-api` directory

### Add `REDIRECT_URI` (i.e. `REDIRECT_URI=http://localhost:3000` if running locally)

### Add `CLIENT_ID`, `CLIENT_SECRET` (i.e. `CLIENT_ID=8db84fbb96fa4422b355b2d97d76dd6a`)

### Add a `PORT` to use to run the server (i.e. `PORT=3001`)

<br/>

<h2 style="color: yellow">Run the project</h2>

To run the project locally, write `npm start` in root directory of `hiitmkr-client` and `nodemon index.js` in root directory of `hiitmk-api`

<br/>

<h2 style="color: yellow">Server end-points</h2>

<h3 style="color: #EEEEEE">/login </h3>

/login allows the user to login using their own Spotify Credentials, authorizing an Access Token and a Refresh Token, valid for 60 minutes

<h3 style="color: #EEEEEE">/refresh </h3>

/refresh allows for the token to be refreshed (this is done automatically)


<h2 style="color: yellow">Next steps</h2>
-return a dynamic list of a users top artists instead of a list of currated artists, so that upon selecting 3-5 favorites, your songs will reflect a greater variety of artists

-use song data to snap to a moment of high intensity or low intensity, instead of relying on a random part of the song

<br />
<br />
<h3>Have a good workout! If you have any questions you can find me on  LinkedIn</h3>

[https://www.linkedin.com/in/danielbutincode](https://www.linkedin.com/in/danielbutincode)

---

<br />

### Credits:

Support and guidence (BrainStation Educators and TAs):

Patrick McCullough: [https://github.com/pgmccullough](https://github.com/pgmccullough)

Pavel Ispranikov:[https://github.com/pavelisp](https://github.com/pavelisp)

Andres Beyra: [https://github.com/abeyra](https://github.com/abeyra)
