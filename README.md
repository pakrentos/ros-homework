# Homework 2
** Nikita Smirnov B18-RO-01 **

## Description

- 9 d.o.f manipulator
- 3 links
- 3 spherical joints

## Run

```
roslaunch ros-homework display.launch model:=urdf/01-myfirst.urdf
```

## Problems

- Installation failed several times, after that I had to reinstall the whole system.
- Turned out that macOS XQuartz does not support OpenGL fully, so it was impossible to verify the urdf using rviz.
- At first, I wanted to create Stewart platform. Then I found out that urdf does not support closed kinematic chains.
- I still don't know how to write scripts for this thing. To be precise, I don't know how to run them.

## Conclusion

I need more time to dive into this thing.
