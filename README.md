# Star Eater
Star Eater is a simple game, where your goal is to eat as many stars as possible.   

Controls are WASD for movement and arrows for rotation. Be careful!  
You have inertia and in space there is no air that would slow you down.  

In config.toml you will find configurable parameters.  
If you want to load your one sky map, you can do this by editing skymap.json.  
Remember to disable random star generation in config.toml!

# Build instructions
To build the project you need to have rust and cargo installed in your system:    
https://www.rust-lang.org/tools/install  

If you have rust installed, just type `cargo run --release` in the root project directory 
(you should see Cargo.toml there) to perform optimized build.  

# More details
Game is written in Rust with use of Bevy as game engine and bevy_rapier3d as physics engine.
Project is simple enough to fit in one file. Data loader is exceptional in this case considering
that config struct can grow quite big and deserves to become a module. 

