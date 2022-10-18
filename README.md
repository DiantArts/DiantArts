Hi! Thank you for passing by.

I'm a passionate student doing my best learning C++ and graphical programming (as well as many other subjects, as long as it is C++) through my personal projects outside my school life.

Some projects I worked (or am still working) on:
- [MmoNetwork](https://github.com/DiantArts/mmoNetwork): A project that was initially a school project, I decided to push it forward to implement it in my future game engine. The goal of this (yet incomplete) project is to use Asio to handle a massive amount of connected clients. Once the base is set up, this project will slowly turn into a project optimized for game engines. I stopped this project to actually start to learn graphical programming.
- [Akanya](https://github.com/DiantArts/Akanya): The first iteration of my biggest personal project I ever started, a Game Engine. I discovered OpenGL with this one but made too many beginner mistakes, such as using the object oriented approach, which made me unable to move forward correctly. While I did not give up the idea of a Game Engine, I decided to step back a bit by starting the project all over again with an ECS approach [EcsGameEngine](https://github.com/DiantArts/EcsGameEngine).
- [EcsGameEngine](https://github.com/DiantArts/EcsGameEngine): This project, which is still a game engine, uses an ECS architecture to correct the problems I had with the OOP in the [Akanya](https://github.com/DiantArts/Akanya) project. Even though it was going well, I realised My ECS implementation was completly dependent to the actual project [EcsGameEngine](https://github.com/DiantArts/EcsGameEngine), especially OpenGL. That is when I decided to move a step back once again and extract the ECS implementation into an extern standalone library. This is how the [xrnEcs](https://github.com/DiantArts/xrnEcs) library started.
- [xrnEcs](https://github.com/DiantArts/xrnEcs): This project has had 2 iterations.
  - The first iteration was the extraction of the library from the [EcsGameEngine](https://github.com/DiantArts/EcsGameEngine) as explained in the description of this project. While the implementation ended up quite stable ([the 0.3 alpha version](https://github.com/DiantArts/xrnEcs/releases/tag/0.3-alpha)), it was hard to implement, use, and awful to update. For that reason, and after trying to use [EnTT from Skypjack](https://github.com/skypjack/entt), I thought about a better and simpler way to implement it, which gave birth to the second iteration.
  - The second iteration is still in developpement and has all external functionalitites extracted to external libraries. This iteration of the project is what gave birth to the xrn suit of project:
    - [xrnBlank](https://github.com/DiantArts/xrnBlank): A repository template that uses cmake and simplifies dependency managment.
    - [xrnCMake](https://github.com/DiantArts/xrnCMake): A cmake library that [xrnBlank](https://github.com/DiantArts/xrnBlank) uses to abstract details of CMake implementation and simplify the usage of external and internal(xrns) dependencies.
    - [xrnLog](https://github.com/DiantArts/xrnLog): A Logger abstracting the [spdlog from Gabime](https://github.com/gabime/spdlog) and [fmt](https://github.com/fmtlib/fmt) libraries to suit xrn projects needs.
    - [xrnUtil](https://github.com/DiantArts/xrnUtil): A simple library of utilities that can always be useful such as time management and a (cool) Optional Reference implementation.
    - [xrnMeta](https://github.com/DiantArts/xrnUtil): A template metaprogramming library that puts most of my reusable meta programmation into a single library so I don't have to implement it again. I mostly use the contraints but the rest may be useful as well.
    - [xrnNetwork](https://github.com/DiantArts/xrnNetwork): A new iteration of the [MmoNetwork](https://github.com/DiantArts/mmoNetwork) project to simplify it by using the xrn suite and my new knowledge. This project just started and I'm fighting in my head to know if I want to work on this one or the  [xrnLanguage](https://github.com/DiantArts/xrnLanguage)
    - [xrnLanguage](https://github.com/DiantArts/xrnLanguage): A programming language inspired by C, C++ and [Carbon](https://github.com/carbon-language/carbon-lang). This project is currently at the design phase and does not have anything to show.
- [VulkanSandbox](https://github.com/DiantArts/VulkanSandbox): A sandbox to learn Vulkan. I have been following a really fantastic guide made by [BrendanGalea on youtube](https://www.youtube.com/c/BrendanGalea) while implementing an ECS approach to the turorial. This project is currently in stand by waiting for the xrn suite to progress. Once it did, I'll push the project forward, starting with networking.

All these projects, even though they are not completed, were very challenging for me for multiple reasons. I learned a lot and will keep pushing them forward until I can finally combine them all into a game engine.

Some other projects I have in my head that I might start:
- Create a sound library, using OpenAL or something else depending on what I find.
- Finishing my [coding style](https://github.com/DiantArts/CodingStyle)

Don't hesitate to let me know what you think of my work at: evan.loiseau@epitech.eu, I would be glad to have external insights.

<!---
DiantArts/DiantArts is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
