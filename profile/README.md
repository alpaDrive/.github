# alpaDrive
A passion project by a couple of auto enthusiasts to bring the latest tech features to those old gas guzzling revving set of wheels laying around in your garage.

>▶️ [Watch on YouTube](https://youtu.be/b1pSNw7addc)

## What's the deal?
In the initial version, we are enabling cloud connectivity in legacy vehicles. The setup consists of a small DIY device that connects to your car's OBD port, pairs via our mobile app and gives you real-time connectivity with the vehicle! We are happy to announce that this system is ready as of v0.1 🎉. It has the following feeatures currently working:
* Live vehicle monitoring
    - Dashboard cluster mirroring
    - Location tracking
* Vehicle health analysis
    - Driving stats (daily, periodic)
    - Health estimation

**Get a quick glimpse here ⬇️**
> **Note** The phone is on mobile data so this is the same as if you were viewing it from anywhere else in the world. For a more convincing demo, see the [video on YouTube](https://youtu.be/b1pSNw7addc).

https://github.com/alpaDrive/.github/assets/50231856/598d5305-a06a-401a-a394-02cda0398999

## Tech stack
This system consists of 3 main components. The software for all of these are open sourced and available in this GitHub organization:
* A central server, written in Rust🦀, that acts as an auth & messaging platform for the vehicle and app. It also manages data storage using a Mongo database, and generates health reports for the vehicle. Find the code [here](https://github.com/alpaDrive/server).
* The software in vehicle, running on the Pi. It manages the hardware and communicates with the car and server. You need to have the hardware set up before being able to use the software. Find the code [here](https://github.com/alpaDrive/vehicle).
* The mobile app, built using the Expo workflow and React Native. It just acts as an interface for the user to view all the data in an intuitive manner. Find the code [here](https://github.com/alpaDrive/app).

## Future plans
We don't plan on releasing this as an end product as of now. However, we do intend on improving the system. As such, any valid contributions are welcome! We look forward to seeing your issues and PR's in our repositories.
