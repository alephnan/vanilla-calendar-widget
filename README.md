# Thoughts

## Backlog

- refactor: Encapsulate widget and state into object
- feat: Dynamically center everything. With the use of floating columns for the buttons and the calendar,
  unless a fixed width is specified, the contents of the container is not centered aligned.
- feat: Make the button a perfect circle
- feat: Provide visual feedback that button is clicked, and add transition
- bug: Remove default styling where a blue box bounds the button when the button is clicked
- refactor: zip the two arrays used for metadata about months, namely English name of the month, and
  days in month into a single array with an object.
- performance: cache calculations for previous months for when they're revisted
- refactor: use a state container and something which tracks state change and re-renders
- refactor: use of single and double quotes should be consistent in JS code
- feat: Show initialization / lazy loading view
- refactor: audit DOM class and selector naming
- performance: use a Fragment to add all cells to calendar in batch
