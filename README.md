# fivedxpl
fivedxp linux loader (2.20.02)

- currently only works with xbox controller

# controls
- y = view change
- a = interrupt
- start = service (use this for inserting coin)
- x = card
- left dpad = toggle test menu
- up / down dpad = test up / down
- right dpad = test enter

# setup
- copy libfivedxp.so, config.json and start.sh to the game folder
- make a folder named ```libso``` and put libcrypto.so.0.9.8 & libprotobuf.so.7 & libssl.so.0.9.8 in it
- make sure to create directories inside save directory
- do ```chmod +x start.sh```
- start the game
- enable test menu
- open game options
- disable ic card r/w use (if offline mode)
- disable ic card vendor use
- disable steering power
- open i/o test and go to i/o interface initialize

# required directories in save directory
- banacoin00
- banacoin01
- billing00
- billing01
- bookkeep00
- bookkeep01
- errorlog00
- errorlog01
- setting00
- setting01

# starting the game
- ```./start.sh```

# TODO
- rewrite jvs + better input handling
- proper terminal fix
- make touch emu
- better input

# credits
https://github.com/jmpews/Dobby
https://github.com/OpenJVS/OpenJVS
https://github.com/drewnoakes/joystick
