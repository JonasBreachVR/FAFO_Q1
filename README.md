# VR Toolkit test - FAFO Q1 2025
## Goal
Test the VR interaction toolkit in Unity6, and get used to its implementations and usages.
The project should contain certain features that show creativity and understanding of the toolkit.
## Ideas
- An escape-room type experience.
    - Move objects to trigger events/find clues.
- Everything is made of primitives.
- Sparse or no UI. Tablet implementation?
    - If there is a UI, I'd like to try and implement it in a locally hosted web server, then display it on a surface.
- Simple puzzle game where the UI is important.
    - Wonky in-game keyboard and mouse controls, used by VR controllers.
- Simple plane game. Three levers to control the plane.
    - One lever for throttle, one for pitch(& roll?), one for yaw.


## Progress
- [x] Set up basic web UI server: https://github.com/JonasBreachVR/fafo_q1_webserver
    - Discovered that showing the UI in Unity is no simple task(for less than $300...)
      - Can probably not do this, currently.