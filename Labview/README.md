# Labview utility for the RN2483 LoRa transceiver

Main files description
----------------------
- Labview project file: <b>bzminds_LoRa_RN2483.lvproj</b>
- User interface/Main front panel: <b>main_FP.vi</b>
- Executable file (windows): <b>builds/bzLoRa_RN2483.exe</b>

Dependencies
------------
- To edit source files: Labview 2011, Ni-VISA
- To just run the executable: Labview runtime engine 2011, Ni-Visa

Usage
-----
- Execute <b>bzLoRa_RN2483.exe</b> inside <b>builds/</b> folder
- In <b>'Settings'</b> tab, choose the appropriate com 'port' and 'baudrate' (default is 57600)
- Run the application
- Status light 'Connected' will turn on and device information will be shown in <b>'RN2483 config'</b> tab
- Go to <b>'Reception'</b> or <b>'Transmission'</b> tab depending if you want listen for incoming packets or transmit them.
- Click on <b>'START'</b>
- Enjoy!
