# Welcome to Yo-kai Watch 2: Redefined!

**Yo-kai Watch 2: Redefined** is a texture Pack for Yo-kai Watch 2, designed to make Yo-kai Watch 2 look like a modern game, simliar to Yo-kai Watch 1 for Nintendo Switch.


# How can I play it?

Yo-kai Watch 2: Redefined is designed **for use with emulators**. The 3DS is not supported for a number of reasons, the most obvious being the resolution of the handheld in the first place. Adding HD Textures to a game running on **2 240p screens** wouldn't make it look any better since the low rendering resolution of the entire game would negate any high resolution assets. If anything, it would look much worse since the original textures are tailored to the low resolution, while these are obviously not.
The file structure is also extremely different. Emulators like **Citra** and **Azahar**, as well as ones for other platforms like Dolphin for Gamecube and Wii have dedicated texture dumping and loading functionality. This takes **all textures being loaded** - in other terms, being translated *from* **a 3DS-usable state** *to* **a PC-usable state** - and spits them out as PNGs (or DDSs, in Dolphin's case), ready for the user to modify to their heart's content.

## Compatibility

Yo-kai Watch 2: Redefined was designed with the German version of Yo-kai Watch 2 Psychic Specters in mind, though English textures are being worked on. You can generally use textures for any language on any other language of the game without breaking anything, but the ones that aren't intended to be used in any given language simply won't be replaced, leaving you with the original texture in its place.
*With the way texture loading works on 3DS emulators, you could even take this texture pack, apply it to a completely different game from a different development studio, and if said game somehow uses a texture that matches exactly (like a grass texture being pulled from the same stock photo for example), it would theoretically be able to load it.*

## Installation
*This tutorial uses Azahar, but Azahar is entirely interchangable with Citra in this regard. If for whatever reason you want to use Citra, you can do that.
The tutorial also assumes you have downloaded the textures you want to use from the "**[Releases](https://github.com/ykwrefined/Yo-kai-Watch-2-Redefined/releases/)**" tab.*
To install the textures, **right click Yo-kai Watch 2 in the Azahar main menu**, then **click "Custom texture location"** (or whatever it's called in your language). This opens a folder named after the game's 'TitleID'. *This ID tells Azahar which game a mod or texture is for.*
Extract **the *.zip* file(s) you downloaded** from the "Releases" tab into **this folder**. It doesn't matter if the textures are in subfolders (I added those to make it more organised), as long as they are in the TitleID folder.
Go back to the Azahar main menu and navigate to **Emulation** (located in the top bar) > **Configure...** > **Graphics** and make sure "**Use Custom Textures**" is checked.
Additionally, you can also check "**Preload Custom Textures**". This, as the name suggests, makes it so all custom textures are loaded before the game starts. If this is **not** enabled, each texture will take a short time (about half a second on my PC with a fairly quick NVME SSD) to load whenever it is used, meaning you will likely encounter a lot of texture flickering.
The **downside** to this setting is that the textures need to be loaded somewhere. That "somewhere" is your RAM, meaning that a chunk of your RAM will be taken up as long as your game is running. It also means that you will be waiting anywhere from half a minute to a few minutes waiting for the game to start up, depending on your storage speeds.
I personally play with the setting on, but your experience may differ.
Finally, make sure your internal resolution (which can be found in the same tab as the "Load custom textures" checkbox) is set **higher than "Native"**. The textures are **8x the normal resolution**, meaning that you can set it **up to 8x** without them becoming blurry. I also recommend enabling Linear Filtering to smooth out edges that can occur when window size and internal resolution don't quite match up.

### And that's it!
Now, simply start the game and enjoy Yo-kai Watch 2 in High Definition!
To update the texture pack, simply download the version you want to update to and choose "overwrite" whenever you are prompted to do so.
Please keep in mind that I can sometimes make mistakes, just like anyone else on this planet, and sometimes textures can slip into folders they are not intended to be in. If this happens, your PC **won't know** that it's supposed to replace a file, meaning it will have **2 files pointing to the same texture**, loading the old one in the process. So, it's safer to delete the old texture pack version from the folder before applying the new one.

# Have fun!
