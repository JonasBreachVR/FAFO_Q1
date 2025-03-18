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


## The UI Experiment
- Set up basic web UI server: https://github.com/JonasBreachVR/fafo_q1_webserver
  - Locally hosted on `localhost:5173`
  - Can be viewed in a browser.
  - Uses Vue3 for implementation.
- Installed and used ShoeLace: https://shoelace.style/
  - Added a simple button and logged it being clicked.
- Discovered that showing the UI in Unity is no simple task(for less than $200...)
  - Can probably not do this, currently.
  - I'd use this, if it came down to it: https://developer.vuplex.com/webview/overview

- What would I do differently?
  - Specifically create the git project within the Webserver folder, and not outside.
    - It would allow me to do `npm install/run` directly in the IDE console.
    - Look a little more into what I'd like to include in the `git-ignore` file.

## What happened?

- This FAFO turned into an experiment more than a small project.
  - I worked on implementing the VR Toolkit in Unity6, and I learned a lot from setting up the project and android settings.
  - I created a locally hosted web server, and was able to configure it to show a simple UI.
    - When it came down to showing it in Unity, I was unable to do so. (For free)
    - I began research on how to send signals between a locally hosted server and Unity.
      - Found a few ways to do this, but didn't spend much more time on actually creating it.
  - Got a smooth locomotion-based XR rig working with the toolkit.
  - Started experimenting with XR Rig settings.
  - Set up a simple scene with a few objects to interact with.
  - Started looking into Unity6's new input system.
    - Played around with a few different control/interaction-modes.
  

During FAFO, I believe I ended up with a lot of knowledge and experience, but not much to show for it.