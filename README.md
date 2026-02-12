# optimus-run
A simple shell wrapper which aims for convinient way of running games.

NVIDIA prime-run was in my case really crappy and had so many issues with NVIDIA render offloading on Linux. Overtime, it burnt me out so I thought to myself, why not make a simple script that did render offloading that prime-run was supposed to do and also apply optimizations for good performance? This is what motivated me to make it, a pretty simple script and when you run a game with it, you gain potential for higher performance ceiling.

For closest experience to NVIDIA's prime-run, you can place the script in /usr/bin, and then you'll be able to run it from anywhere without having each file for each game.

# optimus-kill
Another simple shell script which aims to kill gamescope and/or gamemode if they linger for too long in the background.
