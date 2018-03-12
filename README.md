** FACSvatar using Crossbar.io as message broker is deprecated.
This project continues with ZeroMQ: https://github.com/NumesSanguis/FACSvatar **

This project uses a variety of software. Check their license information before using any of the code here.
Code made by me is under the "GNU General Public License v3.0".

# FACSvatar

Framework to create high-quality avatars based on Manuel Bastioni Blender plugin and control their facial expressions in game engines like Unity3D and Unreal Engine (not yet implemented) with an intermediate dataformat based on the [Facial Action Coding System (FACS)](https://en.wikipedia.org/wiki/Facial_Action_Coding_System "https://en.wikipedia.org/wiki/Facial_Action_Coding_System") by Paul Ekman. FACS data is retrieved through [OpenFace](https://github.com/TadasBaltrusaitis/OpenFace "https://github.com/TadasBaltrusaitis/OpenFace").

The purpose is too offer an easy to customize, open source framework that enables both the animation of avatars with just a webcam, and use the same data for analysis by Embodied Conversational Agents (ECA). A video and poster can be found on the [FACSvatar homepage](https://surafusoft.eu/facsvatar/ "https://surafusoft.eu/facsvatar/")

Running (so far) both on Windows and Linux (Ubuntu).


# Setup instructions
- docker run -it -p 8080:8080 crossbario/crossbar

## Software
* [Blender](https://www.blender.org/) + [Manuel Bastioni Lab addon](http://www.manuelbastioni.com/)  (create human models)
  * [MBlab wikia](http://manuelbastionilab.wikia.com/wiki/Manuel_Bastioni_Lab_Wiki) 
* [OpenFace](https://github.com/TadasBaltrusaitis/OpenFace)  (extract FACS data)
* [Unity 3D](https://unity3d.com/) 2017.2 (animate in game engine)
* [Crossbar.io](https://crossbar.io/) (Publisher-Subscriber model)
* [Docker](https://www.docker.com/)  (containerization for easy distribution)

