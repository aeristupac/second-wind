# Install Second Wind 1.14 (beta)

The same guide, with download links, is online at <http://192.241.157.186/install>.

Second Wind needs the **US edition** of PlayStation All-Stars Battle Royale (disc, `BCUS98472`).

## RPCS3 on Windows

1. Set up RPCS3 normally and add the game, so it shows in RPCS3's game list.

1. Download [Second Wind for Windows](http://192.241.157.186/download/SecondWind-Windows.zip) and unzip it.

1. Double-click **Install Second Wind**. It makes its own copy of the game update and updates that copy. Your normal RPCS3 stays as it is.

1. Play from the new **Second Wind** icon on your Desktop. It checks for updates when it starts.

## RPCS3 on Mac

1. Set up RPCS3 normally and add the game, so it shows in RPCS3's game list. Second Wind needs macOS 15 or newer.

1. Download [Second Wind for Mac](http://192.241.157.186/download/SecondWind-Mac.zip) for Apple Silicon (M1 or newer), or [Second Wind for Intel Mac](http://192.241.157.186/download/SecondWind-Mac-Intel.zip). Unzip it.

1. Right-click **Install Second Wind.command**, choose **Open**, then **Open** again.

1. Play from the new **Second Wind** app on your Desktop. It checks for updates when it starts.

## PS3 with HEN or custom firmware (beta)

You need webMAN MOD on the PS3, and a PC or Mac on the same home network.

1. Install the game's official update on the PS3 if it asks (start the game once while online).

1. Set the PS3's DNS as in [the DNS steps below](#ps3-dns-steps).

1. Download [Second Wind for PS3](http://192.241.157.186/download/SecondWind-PS3.zip), unzip it and run it on your PC or Mac with the PS3 turned on. It finds the PS3, saves a backup of the game files on your computer, and copies Second Wind over.

1. Each time you play, keep Second Wind for PS3 open on your computer and start the game. It turns Second Wind on within a few seconds of the game starting.

If you use webMAN's R2+Triangle combo before signing in, start the game and let Second Wind turn on **first**: the combo switches off the connection Second Wind uses.

## Unmodded PS3 (beta)

An unmodded PS3 only accepts Sony's own updates, so it can't get Second Wind's changes (Ranked 1v1, items off, balance). It can still play online through our server with the DNS steps below.

## PS3 DNS steps

1. **Settings** › **Network Settings** › **Internet Connection Settings** › **Custom**.

1. Keep your usual connection choices until **DNS Setting**, then pick **Manual**.

1. Primary DNS and Secondary DNS: `192.241.157.186`

1. Leave the rest as it was, save, and test the connection.

To undo it, set DNS Setting back to Automatic.

## Special cases

### My game has no update (version 1.00)

That's fine on RPCS3: the installer downloads Sony's official 1.12 update itself, then updates it.

### RPCS3 says the firmware is missing

The installer downloads the PS3 system software from Sony's own update server and installs it for Second Wind.

### I have the digital version, or a European copy

Not supported yet. The US digital version is planned; ask on the Discord for news.

### How do I remove it?

RPCS3: delete the Second Wind app or shortcut (Mac kits include an uninstaller); your normal RPCS3 was never changed. PS3: Second Wind for PS3 has a Restore option that puts the backed-up game files back.
