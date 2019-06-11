# React Hackathon

![Homepage](/readme-images/homepage.png)


Web application powered by Deezer, a music streaming API. It allows users to search for artists and provides results sorted by albums, with album covers, tracklisting and samples.

### Timeframe
1.5 day



## Technologies used

* React
* Axios
* Javascript
* SCSS
* Bulma
* HTML
* Git
* Webpack
* Ajax
* Deployment via heroku
* Deezer API


## Installation

1. Clone or download the repo
1. ``npm i`` to install dependencies
1. ``npm run serve`` to view in browser

### Project Brief

Working as a team and pair programming, create a website using a third-party API and React.

<!-- ## Overview

Initial goal: a website to display Albums

As a first instance, we created a website that when searching for an artist, it displays all the albums related to that search. This is the result of an axios request to deezer's API, using the search value as a query string.
We then made an album show page where we displayed the album's cover, artist and duration. On click, you could also see the tracklist.


```
getData() {
  axios.get('https://cors-anywhere.herokuapp.com/api.deezer.com/search/album', {
    params: {
      q: this.props.match.params.query
    }
  })
    .then(res => {
      console.log(res.data)
      this.setState({ albums: res.data.data })
    })
}

```
As an extra feature we decided to add a small audio sample to each track, provided by Deezer's API.

We decided to improve user experience, to have the audio tracklist on the same page as the album.





### Introduction


## Process


### Challenges


### Wins


## Future features -->
