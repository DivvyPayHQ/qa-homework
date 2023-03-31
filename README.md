## Elixir SDET homework assigment

Explore https://qa-homework.divvy.co/, and automate test cases for some or all of the challenges using Elixir.

Your solution should cover both happy path (expected), and sad path (error state) test scenarios for the use cases present on this web app. 

Feel free to take liberties on the architecture and libraries used, but be prepared to explain your decisions. Refer to the documentation for [Hound](https://github.com/HashNuke/hound) if needed. You are also welcome to add other Elixir packages if desired.

More than anything this challenge is meant to showcase your skill in test writing as well as your fundamental coding principles, so don't worry about doing something odd or contrived if it helps you demonstrate your abilities better.

Bonus: Choose at least 1 request from https://reqres.in/ and write at least one api test for that request (double bonus if this is done in elixir, in the same project as the browser automation portion.)

When finished, submit the challenge as a github link from your personal github and notify your recruiter (please keep the name of the repo as "homework")


## Getting Up and Running

- Download the latest version of chromedriver and ensure that your version of chrome is up to date as well. If your local chrome browser version doesn't match the version of chromedriver you install, you will likely run into "Invalid Session" errors upon starting the tests.
- Install a recent version of Elixir
- Once Elixir is installed, run `mix deps.get` from the application root directory to install Elixir dependencies
- Start chromedriver with `chromedriver --port=9515`
- Run the sample test to navigate to google with `mix test` from the application root directory. If your browser navigates to Google, you're ready to go!


