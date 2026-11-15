# FakerDetector

Made by turkicc.

**[Download the latest FakerDetector.exe](https://github.com/YasasinTurkiye/FakerDetector/releases/latest)** (under *Assets*).

FakerDetector checks whether a Minecraft player's connection runs through a second PC
(a Minecraft man-in-the-middle setup such as Faker) during a screenshare.

## How to use it

1. The player joins the server in Minecraft and stays connected.
2. Run `FakerDetector.exe` on the player's PC and allow administrator rights when Windows asks.
3. Press **Scan** and wait about 30-40 seconds.
4. Read the verdict and the findings. **Save report** stores the result.

It changes no settings. It sends a few test connections, pings and traceroute probes, reads the
network settings, and briefly captures the Minecraft connection to check it; nothing from the game
session is stored. Everything it unpacks is deleted when the window closes.

A result without findings is never proof that nothing is in between. Use it together with your
server's own checks.
