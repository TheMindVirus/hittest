# hittest
3D Hit-Testing and Control Example in Unity 2021 (Experimental)

Please note that the code in this repository is **Experimental** \
and demonstrates how much Unity has overcomplicated the simple task \
of hittesting and ray-tracing of objects and child objects.

Demo: https://themindvirus.github.io/hittest/Output

![testing](https://github.com/TheMindVirus/hittest/blob/main/testing.png)

The RaycastHit C# Object and Colliders are intended for cursor hittesting, \
not lighting and path-tracing as the name may suggest. \
It is suggested that this API be completely re-engineered in Lua, \
as is the standard used by Tabletop Simulator.
