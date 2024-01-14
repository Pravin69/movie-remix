<h1 align="center">
	Movie remix 🎬
</h1>
<h4 align="center">Movie-remix is the ultimate app for movie lovers who want to discover and watch the best movies and TV shows according to the latest trends.</h4>

<p align="center">
    <img src="https://img.shields.io/badge/%E2%9D%A4-Made%20with%20Love-blue"  alt="Gitter">
</p>

<p align="center">
  • <a href="#key-features">Key Features</a> 
  • <a href="#how-to-use">How To Use</a> 
  • <a href="#app-demo">App demo</a> 
  • <a href="https://movie-remix.vercel.app/">Live Demo</a> 
  </p>

<p align="center">
<img src="https://github.com/Pravin69/movie-remix/blob/main/demo/app_ss_remix.jpeg?raw=true" alt="Movie remix Capture" style="max-width: 100% !important">
</p>

## Key Features

- **Infinite Scrolling and Lazy Loading** :-

  - Implemented a dynamic loading technique that loads more content as the user scrolls down the page, improving the user experience and performance.

- **Global State Management** :-

  - Utilized Redux to manage the global state of the application, ensuring seamless data flow and a responsive user interface.

- **Sort and Filter** :-

  - Users can sort and filter movies and TV shows by genre, popularity, rating, and release date, customizing their preferences and finding the best content for them.

- **Top Movies and TV Shows** :-

  - Users can stay updated with the top movies and TV shows based on daily and weekly rankings, discovering the latest trends and popular choices.

- **Skeleton Structure** :-
  - Used skeleton structure to display a placeholder UI while the content is loading, creating a smooth and elegant user interface.
- **TMDB API** :-
  - [Used the TMDB API](https://developer.themoviedb.org/docs/getting-started)[1](https://developer.themoviedb.org/docs/getting-started) to fetch movie and TV show data, providing a rich and reliable source of content for the app.

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line :

```
# Clone this repository
  git clone https://github.com/Pravin69/movie-remix

# Go into the repository
  cd movie-remix

# Install app dependencies
  npm install

# Set up your Tmdb account

# Configure environment variables by creating .env file in the directory and copy the content of env.example file in .env file, and fill it with your own secrets.
  cp env.example .env

# Start app in  terminal.
  npm run dev
```

## App Demo

![Demo](https://github.com/Pravin69/movie-remix/blob/main/demo/app-gif.gif?raw=true)

## You may also like... 🙂

- [Apna-Shop](https://github.com/Pravin69/mern-ecommerce) - An e-commerce platform
- [Share-and-Fun](https://github.com/Pravin69/Share-and-Fun-Web-app) - A social media web-app
