list_pcap_devices
=================

Simple program to list system devices that can be used by the WinPcap driver.


### System requirements
* Windows with Visual Studio
* CMake
* WinPcap driver and developer's pack


### Installation
1. Download and unzip resp. checkout the repository into any folder.
2. Start the file runCMake.bat in the project root folder, e.g. by double-clicking it in the file browser.
3. If successfull, this will generate a file "(project_root)/built/list_pcap_devices.sln".
4. Open that file with Visual Studio and compile (e.g. choosing menu Build/Build Solution, or pressing F7)
5. Run the program
  * In Visual Studio, in the Solution Explorer Window right click on "list_pcap_devices" and from the context menu select "Debug/Start new instance"
  * Or start "(project_root)/build/Debug/list_pcap_devices.exe" from file browser or console
6. The program should output the list of devices that can be used with the WinPcap driver. Exit the program with pressing any key.
