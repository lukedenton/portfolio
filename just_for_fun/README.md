# Just For Fun
These are small projects that I've worked on, basically, just for fun. I either wanted to learn how to use a new technology,
figure out a way to implement UX from another website, or just solve a game!

**Table of Contents**
1. [Cube Colouring Game](https://github.com/lukedenton/portfolio/tree/master/just_for_fun#keeping-talking-solver)
2. [Keep Talking Solver](https://github.com/lukedenton/portfolio/tree/master/just_for_fun#keeping-talking-solver)
3. [Elevator Saga](https://github.com/lukedenton/portfolio/tree/master/just_for_fun#elevator-saga)
4. [Google Music Header - JSFiddle](https://github.com/lukedenton/portfolio/tree/master/just_for_fun#google-music-header)

## ThreeJS Colouring Game

This game came about when I was browsing the examples on the ThreeJS demo page, and found this example of a cube made of spheres.
When your mouse hovers over a sphere, it will change colour. I quickly found myself trying to colour in all of the spheres
but found it hard to know when I was done.

To create the game, I simply took the ThreeJS example, which is available on their demo page, and added a counter for how
many spheres have been coloured, a timer to track how long it takes to colour in all the spheres, and then added some minor tweaks
to the example code in order to track how many spheres where left to be coloured.

[Cube Colouring Game](ubecolouringgame.netlify.app)

## Keep Talking Solver

Keep Talking and Nobody Explodes is a very fun VR game. As a way to learn VueJS v2, I decided to create a "Keep Talking Solver".
The title is a bit misleading as it doesn't really solve the puzzles, it just helps with solving them. It's kind of like
having someone with a photographic memory on your team, who doesn't have to look at the defusal manual. The structure of
most of the puzzles meant it was a perfect excuse to create something using a new technology.


## Elevator Saga

[Elevator Saga](http://play.elevatorsaga.com) is a neat Javascript programming game that I found online. Basically you have to write the logic for
an elevator (and then eventually a set of elevators) to move between floors, picking up people and dropping them off.

I managed to write a solution that gets through most of the levels. The ones that my solution has trouble with is in elevator
movement efficiency, and not making people wait X seconds. My solution manages to pass the rest of the levels - but not
necessarily on the very first go, sometimes it depends on the input, i.e. when and which floor people call the elevator.

[ElevatorSaga Solution on GitHub](https://github.com/denno020/elevatorsaga)

## Google Music Header
I recently signed up with Google Music for streaming music, and when looking through the site and the various music
available, I noticed what I thought to be a very neat UX for displaying a large artist image. I wanted to try
and replicate this UX, so I tried it out in JSFiddle.

I didn't want to place any restrictions on myself like creating it with only CSS, so I just went for it! CSS and Javascript

[Google Music Header on JSFiddle](https://jsfiddle.net/denno020/s6p61oft/)
