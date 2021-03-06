# SourceSage Frontend
Our frontend codebase is written primarily in [ES2015/ES6](https://babeljs.io/docs/learn-es2015/), utilises [Flux architecture](https://facebook.github.io/flux/docs/overview.html) for application state management while using [React](https://facebook.github.io/react/) for making UI components.

We're on a lookout for passionate frontend developers who are always finding ways to reduce page load times for users. You strive to delight users with your creations. You learn fast in the face of ever-changing landscape of the web frontend. You can submit pull requests to the backend to fix endpoints that you directly interact with. And you know how to convert static photoshop designs from our UI/UX designer into UI components.

Requirements:
* Knowledge of the browser environment, DOM and Web API's
* Be able to code up basic responsive UI
* Awareness of the cross-browser implications of your code - [caniuse.com](http://caniuse.com) is your friend.
* Have enough CSS knowledge to do basic layout using Flexbox, grids, floats, % widths, etc.
* Have enough CSS knowledge to translate a given photoshop design into HTML and CSS.
* Can use Chrome DevTools, or equivalent, for debugging and performance tuning.
* Learn fast
* Sensitive to performance - actual and perceived page load times

Other Programming Skills:
* Functional programming knowledge
* Basic version control - we use `git`
* Knowledge of other programming languages - we use `python` for our backend API.

To contribute immediately, you would probably have to know these libraries:
* [Redux](https://github.com/rackt/redux)
* [React](https://facebook.github.io/react/)
* [ES2015](https://babeljs.io/docs/learn-es2015/)
* Used some build tool before. (We use [webpack](https://webpack.github.io/) at Sourcesage)
* Be familiar with [Github Flow](https://guides.github.com/introduction/flow/)

## 1-minute Challenge
Write javascript code so that the expression
```javascript
add(5)(2)
```
evaluates to `7`.

## 5-minute Challenge
* Code up a "Like" button similar to that of Facebook, in a declarative style. Be explicit about the states that the component could take, and how the UI should render for any given state. You should probably use React.

## 10~15-minute Challenge
* Suppose you have to make API calls to 2 endpoints `/posts`, and `/comments`. In order to get the full `comments` for a `post`, you need to supply the `/comments` endpoint with a `comment_id` in `POST` JSON body, which you can get from `post` data returned from the `/posts` endpoint. The data returned from `/posts` looks like this
```javascript
{
  "id": 7,
  "body": "This is a sample post.",
  "comments": [1, 5, 7, 12]
}
```
  * Write out the code, in javascript, to retrieve the `post` together with its full `comments`.
