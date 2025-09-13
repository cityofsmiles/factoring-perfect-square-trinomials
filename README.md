# Factoring Perfect Square Trinomials Flashcards

This web application is an interactive flashcard tool for practicing how
to factor perfect square trinomials.\
It is hosted at:
<https://cityofsmiles.github.io/factoring-perfect-square-trinomials/>

## Features

-   Randomized set of 10 flashcards each session.
-   Input answers with real-time correctness feedback.
-   Navigation between flashcards (Previous / Next).
-   Submit answers to view a final score and detailed answer key.
-   Retry with a fresh set of randomized flashcards.

## Usage

1.  Visit the hosted app at [this
    link](https://cityofsmiles.github.io/factoring-perfect-square-trinomials/).
2.  Read each trinomial question displayed on the flashcard.
3.  Type the factored form in the input box.
    -   Example: `(x - 9)^2`
4.  Use **Previous** and **Next** to navigate between cards.
5.  Press **Submit** when finished to view your score and answer key.
6.  Click **Try Another Set** to start over with new flashcards.

## Development

This project is built with:

-   [React](https://react.dev/)\
-   [Framer Motion](https://www.framer.com/motion/) for animations

### Running Locally

1.  Clone the repository:

    ``` bash
    git clone https://github.com/cityofsmiles/factoring-perfect-square-trinomials.git
    cd factoring-perfect-square-trinomials
    ```

2.  Install dependencies:

    ``` bash
    npm install
    ```

3.  Start the development server:

    ``` bash
    npm run dev
    ```

### Production Build

To create a production build:

``` bash
npm run build
```

The app fetches flashcards from `flashcards.json`.\
- In **development mode**, it loads `/flashcards.json`.\
- In **production mode**, it loads from the GitHub Pages URL.

## Author

Developed by **Jonathan R. Bacolod, LPT**.

------------------------------------------------------------------------

This project is for educational purposes to help students practice
factoring perfect square trinomials.