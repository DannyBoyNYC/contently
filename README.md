# Technical Assessment - Javascript and React

## Notes

Live: https://deverell-contently-weather.netlify.app/

## Solves for:

- ✅ As a user, I would like to search for the current weather in my area
- ✅ As a user, I would like to see the 5-day forecast
- ✅ As a user, I would like to share the URL of the weather in my area
  and see the results
- ✅ As a user, I would like to toggle between celsius and fahrenheit

Four hours was not enough time for me to properly complete the project 🕧, but I did manage to rough it out in about half a day (and wouldn't mind coming back to it).

Written using class components because that's what I'm using in the day job and I was hoping would be faster. Wouldn't mind refactoring to hooks as part of a clean up.

There are a number of TODOs ✅ in the code and I would have added more so here is a short list of issues I would have looked into given more time:

- The data fetching is pretty raw 🥩 and most do not have error handling 🙀. (Would normally used Promise.all)
- I did not properly implement the sharing mechanism (would normally install React Router for this) but there is a minimal implementation that should at least give an idea of my eventual approach
- In terms of UI/UX I would normally have the 5 day forecast visible by default but for some reason thought the requirements said otherwise 🤷🏼‍♂️
- I didn't like the initial starting point being a lonely input field so I decided to query the ipapi for an initial weather view
- I did not have time to implement testing 😿, perhaps you could request some?
- Didn't add loading indicators...

## Instructions

An Open weather API key is required. Rename `.env.sample` to `.env` and add your key.

Run using `$npm install` and `$npm start`.

---

## Summary

The purpose of this short assessment is to gain some initial insight in to your
coding style, practices, thought processes, and attention to detail. It is
_not_ intended to be a strictly graded test with specific scores determining
a "pass" or "fail". Just focus on solving the problems outlined how you would
at your current or any other team.

Note that some of the user stories are ambiguous. There are many possible and/or
acceptable solutions to these problems. Use your best judgement to determine
what an appropriate solution is. It would be helpful to also demonstrate or
explain how you came to your conclusions. You may be asked to explain your
solutions if it's not immediately clear what your reasoning was. Additionally,
you may be asked to pair with a Contently engineer to further expand on your
work.

## Instructions

- [Create either a public or private duplicate of this repository](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/duplicating-a-repository).
- Time-box your efforts to 2 to 4 hours.
- Setup application
  - [ ] `npm install`
  - [ ] `npm start`
- Solve for several or more of the following problems:
  - [ ] As a user, I would like to search for the current weather in my area
  - [ ] As a user, I would like to see the 5-day forecast
  - [ ] As a user, I would like to share the URL of the weather in my area
        and see the results
  - [ ] As a user, I would like to toggle between celsius and fahrenheit
- Considerations for the work you submitted:
  - [ ] Code actually works.
  - [ ] Application is bootable and usable.
  - [ ] Unit, integration, feature, and or end-to-end testing considered.
  - [ ] Code is of sufficient quality and tidiness.
  - [ ] Includes documentation on how to utilize new features / updates.
- Commit your work with appropriate and informative git commit messages.
- Push your work up to your duplicated git repository (on Github).
- If your repository is private, give the following users access:
  - [ ] [@briandangerflynn](https://github.com/briandangerflynn)
  - [ ] [@jamesconant](https://github.com/jamesconant/)
  - [ ] [@nethanelkohen](https://github.com/nethanelkohen)
- Create a pull request in your repository:
  - [ ] Must target your master branch from your feature branch.
  - [ ] Must list the problems (from above) that you are addressing in your
        PR.
- Email Contently staff to let them know your Pull Request is ready for review:
  - [ ] Email [jconant@contently.com](jconant@contently.com)
- Contently staff will review your code, possibly asking questions or providing
  suggestions. We will attempt to review your assessment in a timely manner
  and simply ask that you attempt to respond in a timely manner as well.
- Once the review is complete, Contently staff will determine the next steps to
  be taken.

## Thanks!

Thank you for taking the time to complete this assessment. As engineers,
ourselves, we are sensitive to the time and energy it takes to go through this
process once, much less at numerous companies. Your interest is greatly
appreciated and we are excited to see if Contently is the next journey in your
career.
