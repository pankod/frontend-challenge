
<div align="center">
    <img width="500"src="logo.jpg" align="center" />
</div>

We are a young and innovative software development house located in the heart of beautiful İstanbul. We leverage agile methodologies, software life cycle best practices and cutting edge technology to deliver perfect solutions reflecting our passion for software development. 

We care about our company culture and invest people to create best teams of highly skilled developers.

## About the challenge

This is a basic test, in which you should be able to write a React app, using the provided screens as reference. You’ll need to get some JSON content, filter, sort and search the data and print it on view.

Although this is a basic exercise, we’ll be looking for simple, well-designed and tested code in the submission.

## Task

Using the provided screens as a reference, you’ll need to build a set of React components to render the app. You’ll also need to request a JSON feed, filter that data, and use the relevant fields. 

We have provided mock movie data as a JSON file. While requesting JSON feed, we also ask you to use Redux for storing incoming data. So this stored data will be used when you build the app and the components.

Use the returned data to display a page of results that matches the given design.

Please include a README with setup instructions, and any tests or other documentation you created as part of your solution.

We also recommend you to use [create-react-app](https://github.com/facebook/create-react-app)  in order not to make basic configuration yourself.



## Design
We've provided a screen [designs](./designs/) for desktop and mobile version. You should follow design measurements in sketch file. 

If you don't have licence for sketch visit their [official](https://www.sketch.com/) website to get a free trial version.

We encourage you to use latest CSS techniques(like flex-box) and responsive design approach.


## Details
You will need to build the following 3 pages with React:

- A “Home” page
- A “Series” page
- A “Movies” page


#### Home Page
Refer to the screens/1-home.jpg screen.

This will be your index.html screen. You will need to display 2 tiles, which link to the “Series” page and the “Movies” page.

#### Series and Movies Pages
Refer to the screens/2-series.jpg and screens/3-movies.jpg screens.

For each page you will need to fetch JSON feed feed/sample.json, then:

- Display the first 21 entries.
- Where the entry has a releaseYear attribute value >= 2010.
- Sorted by the title attribute value in ascending alphanumeric order.
- There will be buttons which works correctly to sort by year and alphanumeric order.

For the “Series” page filter on:

- Where the entry has a programType attribute value of series

For the “Movies” page filter on:
- Where the entry has a programType attribute value of movie


Search bar start searching when typing 3 characters and show related movies or series on the screen. The delay in milliseconds between when a keystroke occurs and when a search is performed.

The attributes you should use to display the entries are:

- title
- images → Poster Art → url

You will also need to handle the loading and error states, of fetching the JSON feed:

- “Loading” state screens/1.1-loading.jpg
- “Error” state screens/1.2-error.jpg


The deployable solution should be built in a folder named dist with an entry point file of index.html.

Please create components for each part of the page (eg. header, content, footer, etc).
Assets are provided in the assets folder.

You can assume that you do not have to support legacy browsers without features such as fetch or flexbox.

## Nice to have 

Here's few suggestion of things we'd like to see:

- Implement solution in TypeScript.

- Implement solution in Next.js.

- Responsive design for tablet device.

- Showing your work through your Git commit history.

- Production grade code (clean, maintainable, reusable code)

- Implement unit tests with Jest and enzyme or react-rest-renderer.


## Submission Guidelines

* Please submit your code by sending a github repo link.

## Project evaluation table

We are evaluating project according to the features which specified table at the below.

First of all, candidates project should have all requirements at base table.

| Base requirements | Point |          
| --- | --- |
| HTML Markup | 10 Points |
| React & State Management | 20 Points |
| Production grade & Best practices | 15 Points |
| Project folder structure | 5 Points |

You will get extra points if have implement bonus features.

| Bonus   | Point |          
| --- | --- |
| Typescript | 15 Point |
| Next.js | 5 Point |
| Git commit history| 10 Point |
| Unit Tests | 20 Point |







