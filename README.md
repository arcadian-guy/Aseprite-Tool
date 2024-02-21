# Aseprite-Tool
Aseprite is a great tool for game developers and animators. Let this tool help you get it for free 😜
Aseprite is a tool for animating 2D sprites, and is preferred by many game devs. Though Aseprite is paid, it is allowed to be built for free from source.
Aseprite Tool just automates the process and this guide just gives you straightforward simple steps to achieve that.

# Prerequisite
-> Skia Library: Download Skia and extract its content to C:/deps/skia. You can get some pre-built packages [here](https://github.com/aseprite/skia/releases).
-> CMake: Download CMake and add it to your system PATH (You get option in installer to ADD TO PATH, just check that). Get it [here](https://cmake.org/download/).
-> Ninja: Download Ninja and place it in C:/ProgramFiles/CMake/bin (You download a zip file and you get an .exe when you open it). Get it [here](https://ninja-build.org/). You need to add this in System PATH by editing Variables.
a) Search environment variables and open "Edit the system environment variable".
b) Press Environment Variables.
c) Click PATH (UNDER SYSTEM VARIABLES) and press Edit.
d) A list will open, click New and add "C:/ProgramFiles/CMake/bin".
e) Make sure to click apply and save before exiting and Restart your computer.
-> Visual Studio 2022: Install Visual Studio 2022 with the Windows 11 SDK component, available under "C++ Desktop Development" workload.
-> Grab latest release source file for Aseprite from [here](https://github.com/aseprite/aseprite/releases). Extract its contents in a new folder named 'aseprite' placed in C: Drive.

# Procedure
1) Make sure there are deps and aseprite folder in C: and all prerequisite has been fulfilled.
2) Grab latest tool release from this repo and put the .bat file in C: Drive.
3) Click Run and let it do all work 😉 (It takes about 3-8 mins depending on hardware).
4) Your aseprite release will be available at "C:\aseprite\build\bin" in form of aseprite.exe 😄

# Conclusion
Aseprite is NOT my product, I am just helping you guys. Don't ask me unnecessary questions about Aseprite. You can learn more at [aseprite](https://github.com/aseprite/aseprite).
Do support the developer [Dacap](https://github.com/dacap) for his and his team's hardwork. You will officially be supporting the project and get official support with easy updates.

To update the built program, delete the old aseprite folder along with aseprite.exe, and grab the new source file and extract it in new folder named aseprite. Finally, re-run the Tool.

# Support
You can raise an issue or contact me through contact details in bio 👋
