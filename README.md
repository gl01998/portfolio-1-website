# Portfolio Project 1 WebXR

Garrett Lowrance · CSCI 4830 Virtual Reality · Dr. Kyle Johnsen

This repo hosts the WebXR builds of my four Unity VR demos. Open `index.html` for the landing page, which links to each demo. Each demo runs in the browser, and on a WebXR-capable headset (such as Meta Quest) you can click **Enter VR** once it loads.

Click [this link](https://gl01998.github.io/portfolio-1-website/) to try the demos for yourself!

## Demos

| # | Demo | Folder | Summary |
|---|---|---|---|
| 1 | Carnival Ride: Sky Swinger | [`CarnivalRide/`](CarnivalRide/index.html) | A 150 m flying-swings tower ride. The star lifts 125 m, spins up to 90°/s and the seats fan out. Watch from the ground or ride in one of twelve seats. |
| 2 | Sports Trainer: Basketball Free Throw | [`BasketballFreethrow/`](BasketballFreethrow/index.html) | Throw a basketball with your real arm motion. The ball has real mass, drag, spin and bounce, and each shot is measured, graded and coached. |
| 3 | Procedural Trainer: Lockout/Tagout | [`ProceduralTrainer/`](ProceduralTrainer/index.html) | Follow the OSHA lockout/tagout sequence to safely clear a jammed conveyor. Out-of-order steps count as mistakes, and you get your time and mistake count at the end. |
| 4 | Scavenger Hunt: Office Tower at Night | [`ScavengerHunt/`](ScavengerHunt/index.html) | Find five target objects hidden among twenty decoys across three themed office floors, using teleport or smooth locomotion. The clock stops when you find the fifth. |

## Built with

Unity 6 (URP), the XR Interaction Toolkit, OpenXR, and De-Panther's WebXR Export for the browser builds. Custom models and skyboxes were generated with Blender Python scripts.