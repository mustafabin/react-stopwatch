[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# React Stopwatch

Recreate a stopwatch in React. Your final product should function similarly to
[this deployed version](http://scary-religion.surge.sh/) of the component.

## Prerequisites

- React
- Components
- State and props

## Instructions

1. Fork and clone this repository.
1. Change into the new directory.
1. Install dependencies.
1. Fulfill the listed requirements.

Please turn in your submission by the deadline on your cohort calendar.

## Requirements

Take the existing markup rendered from the `Stopwatch` component in
[`src/Stopwatch.js`](src/Stopwatch.js) and change into a fully functioning
component. This means that you only have to add functionality - not markup or
styling - to the existing code!

## Steps to Take

1. Add a `constructor` method and initialize state with a `counter` property to
   track the incrementing time. (You may need additional state properties later
   on)
1. Create a `handleStart` method that calls setInterval() and updates `counter`
   every second. (Make sure to use `setState` to update)
1. Include an `onClick` attribute on the start button which calls `handleStart`
1. Replace the `0` in the `h1` heading with your `counter`.
1. Next you will need to create `onClick` event attributes for reset and pause
   and associated methods for each.

> **Hints**..._Shhhhhh!_ You will also most likely need to include an additional
> attribute in your constructor method that keeps track of your current
> interval. If you have an active interval, then don't let the start button be
> fired again!
>
> You can use `clearInterval` to stop the current interval!

## Resources

- [Forms in React](https://facebook.github.io/react/docs/forms.html#controlled-components)
- [Components and Props](https://facebook.github.io/react/docs/components-and-props.html)
- [Adding State to a Component](https://facebook.github.io/react/docs/state-and-lifecycle.html#adding-local-state-to-a-class)
- [Thinking in React](https://facebook.github.io/react/docs/thinking-in-react.html)

## Plagiarism

Take a moment to refamiliarize yourself with the
[Plagiarism policy](https://git.generalassemb.ly/DC-WDI/Administrative/blob/master/plagiarism.md).
Plagiarized work will not be accepted.

## [License](LICENSE)

1.  All content is licensed under a CC­BY­NC­SA 4.0 license.
1.  All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.
