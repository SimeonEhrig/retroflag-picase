# retroflag-gpi case (gpi case only)
Turn switch "SAFE SHUTDOWN" to ON.

For RetroPie:

1. Make sure internet connected.
2. Make sure keyboard connected.
3. Press F4 enter terminal.
4. In the terminal, type the one-line command below(Case sensitive):

wget -O - "https://raw.githubusercontent.com/RetroFlag/retroflag-picase/master/install_gpi.sh" | sudo bash

--------------------
For Recalbox
1. Make sure internet connected.
2. Make sure keyboard connected.
3. Press F4 first. And then press ALT-F2 enter termial.
4. User: root Password: recalboxroot
5. In the terminal, type the one-line command below(Case sensitive):

wget -O - "https://raw.githubusercontent.com/RetroFlag/retroflag-picase/master/recalbox_install_gpi.sh" | bash



# retroflag-picase (nespi+, superpi, megapi case)
RetroFlag Pi-Case Safe Shutdown

Turn switch "SAFE SHUTDOWN" to ON.

--------------------

Example for RetroPie:

-------------------Multi Switch Shutdown-----------------
Updated: 2019.2.14

Multi Switch Shutdown with advanced shutdown features for more natural behaviour:

If you press restart if emulator is currently running, then you will be kicked back to ES main menu.

If you press restart in ES main screen, ES will be restartet (no reboot!), good for quick saving metadata or internal saves.

If you press power-off then Raspberry will shutdown

All metadata is always saved

Multi Switch Shutdown by crcerror at here https://github.com/crcerror/retroflag-picase

-------------------Multi Switch Shutdown-----------------

1. Make sure internet connected.
2. Make sure keyboard connected.
3. Press F4 enter terminal.
4. In the terminal, type the one-line command below(Case sensitive):

wget -O - "https://raw.githubusercontent.com/RetroFlag/retroflag-picase/master/install.sh" | sudo bash

--------------------

Example for RecalBox:
1. Make sure internet connected.
2. Make sure keyboard connected.
3. Press F4 first. And then press ALT-F2 enter termial.
4. User: root Password: recalboxroot
5. In the terminal, type the one-line command below(Case sensitive):

wget -O - "https://raw.githubusercontent.com/RetroFlag/retroflag-picase/master/recalbox_install.sh" | bash


Example for lakkatv:
https://github.com/marcelonovaes/lakka_nespi_power

Example for Raspbian:
1. Make sure internet connected.
2. Make sure keyboard connected.
3. In the terminal, type the one-line command below(Case sensitive):

wget -O - "https://raw.githubusercontent.com/RetroFlag/retroflag-picase/master/raspbian_install.sh" | sudo bash

Example for Kodi (LibreElec):

**Method A (via ssh):**
1. Get your raspberry IP: Settings > Sytem Information > Network
2. Connect via ssh from your computer: `ssh root@<your-ip-address>`. Default password is `libreelec`
3. Copy&Paste the command below:

`wget -O - "https://raw.githubusercontent.com/RetroFlag/retroflag-picase/master/libreelec_install.sh" | bash`

**Method B (directly to your raspberry)**
1. Make sure internet and keyboard are connected.
2. Press CONTROL+ALT+F3 to enter the terminal.
3. User:root Password:libreelec
4. In the terminal, type the one-line command below(Case sensitive):

`wget -O - "https://raw.githubusercontent.com/RetroFlag/retroflag-picase/master/libreelec_install.sh" | bash`
