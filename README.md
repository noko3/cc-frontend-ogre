Front-end is what user interacts with (3D rendering engine, UI, etc.)

ChanCity (The Game) is designed to have multiple front-ends for the following reasons:
1. CryEngine has better graphics than OGRE out of the box, brigade3 is even better
2. Having an API and some different compartments is always better than having a large blob as the former is easier to write, debug and replace if needed
3. LULZ

No documentation yet, consider these sources as the reference material or kick OP for docs

CC front-end must implement the following:
1. client <-> frontend API
2. 3D rendering engine (OGRE)
3. Audio output engine (OpenAL)
4. User input engine (keyboard, mouse) (OIS or SDL input)
5. ???
6. PROFIT!!!

CC front-end is better to have the following implemented:
1. Scripting (automation)

Editor is an _optional_ module of CC frontend. It should implement the following:
1. Map editor (openstreetmap-style or so)
    1.1. Pedestrian path editor
    1.2. Vehicle path editor
2. World geometry editor
3. Geometry editor for small things
4. WYSIWYG shader editor
