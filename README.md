# About me
Hi i am Dennis.
I am a 27 year old Game Engineering Bachelor of Science Student.
I mainly solve problems in C/C++, C# and Python.


Currently employed at: -
For Business Inquiries only: kden404@protonmail.com

## Current Tech Stack in experience order top = most experience:
Languages:
- Python
- C/C++
- C#

Build Tools:
- CMAKE

Frameworks:
- Wwise
- Unity
- OpenGL
- Unreal Engine (I hate this one)

## current open source projects:

### DLLSoundWwise -  An Audiokinetc Wwise Soundengine Abstraction Layer for use in Vektoria-Engine (Bachelor thesis) - C++:
#### Metadata:
Published: Q4 2026
Published at: https://www.hs-kempten.de/fakultaet-informatik/zentrale-einrichtungen/computerspiel-zentrum-games/vektoria

#### Description:
The Vektoria game Engine which is currently mostly used by (Former) Students of University of Applied Sciences Kempten or other mostly scientific Institutions is a panocratic modular 3D Game Engine.--
It's purpose is of educational Nature and used by Game Engineering Students at Universities to learn how to handle a Scenegraph like Game Engine.--
The Engine is actively developed by Prof. Dr. Tobias C. Breiner aswell as Bachelor- and Master thesis Students.--

During Development i was able to use my knowledge about Software Architecture which i learned at my time at the Reasearch project "Projekt Adler" at University of Applied Sciences Kempten.--
For that integration to be successful it was necessary to treat it as a plugin/add on and not as a full integration into existing not open source systems due to the major differences in architectural design.--
I defined Objects with the purpose in making the interaction with the Engine more Natural. Sound Events, RTPC's, SoundBanks all received their own Objects which handle a lot of the ID's Wwise Relys on.--
I Defined Soundemitters and Soundlisteners aswell which are Gameobject like objects which are the parts of the Engine actually relying on (public) parts of the Vektoria Engine.--

#### Goal of the project:
I decided to write a Sound Engine Integration because of the amount of problems many students had when it was their turn to integrate soundeffects and interactive music into games developed using Vektoria-Engine.--
My goal was creating the module with useability in mind, therefore it is necessary to give students as much freedom as possible while also making the use as easy as possible.--
To ensure the freedom i designed the Plugin so it doesn't rely on proprietary interfaces of Vektoria-Engine.--
Therefore it is possible to give the students the ability to recompile the plugin using newer Versions of the WwiseSDK they decided to use in their games.--
Another goal was the backwards compatibility to the Microsoft Visual Studio only environment Vektoria natively runs on.--
To ensure the plugin also compiles in the upcoming years a CMake build solution was created from which the Microsoft Visual Studio project is generated from using the cmake cli.--
Since i hate Microsoft Visual Studio i used CLion during the entire development of the Plugin only resorting to Microsoft Visual Studio during initial testing until my CMakeLists for VektoriaApp Projects worked.--
I provided the CMake files to Tobias C. Breiner so he can include them in upcoming Vektoria Releases to assist his efforts to make Vektoria Available for other Platforms.--


## current closed source projects:
### "GLED" - An OpenGL Engine (OpenGL, C++):
Current development was moved to closed source a few months ago.--
The Engine heads into a much more modular way of handling things than planned and due to the modular design the repository will remain privately managed.--
I redesigned the entire Engine Architecture after it was moved to closed source.--
I will most likely abstract DLLSoundWwise in Order to use it in the redesigned Engine.--
