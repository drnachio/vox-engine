![Vox Engine Logo](./resources/vox.png)

# Vox Engine 

3D Voxel Based Engine for Real Time Persistent Worlds

## General Description

This 3D Engine was created to be able to generate the PinHub Project and designed to be used in many 3D Voxel Based persistent real time games in the future.

I will use [BabylonJS](https://www.babylonjs.com/) as the main 3D Engine because of the TypeScript class implementation, structure and performance.

To implement the communications we will base the development in NodeJS with Socket.IO and Redis servers to allow horizontal scaling of the system.

Some of the concepts and ideas come from a previous project called `mundo` that we created more than 10 years ago, facing a lot of technical limits that now do not exist.

## Main Modules

- Vox Engine Client
- Vox Engine World Servers
- Vox Engine Services