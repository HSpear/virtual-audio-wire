virtual-audio-wire (VAW)
==================
  The Virtual Audio Wire (VAW) is an open source Virtual Audio Device (VAD) project its function is to provide
  Virtual Audio Devices for multimedia applications such as Adobe Audition, Sony Sound Forge, AIMP Player,
  Broadcasting softwares etc in Windows platform (similar to JACK Audio Connection Kit(open source but 
  use ASIO - technology), Virtual Audio Cable (VAC) and Virtual Audio Streaming (VAS)).As we know that commercial
  softwares are not free and not open source. In this Project Virtual Audio Wire (VAW) we introduce an open source 
  equivalent of Virtual Audio Cable (VAC).We welcome those who are intrested in this project and expect your 
  contributions,/suggesions in this project. Here we provide MSVAD sample program as an initial code.
  You are allowed to modify the code partialy or completely.
  
VAW program requirements:
------------------------
1. Install as System Driver(ie sys extension files) requires Windows     driver level programming knowledge 
   (prefered languages C/C++)needs WinDDK,Visual Studio Professional.
2. Supported formats:
   	Sampling Rate:- 8000 to 1000kHz
   	Bit depth:- 8 to 32bit
   	Channels:- 1, 2.0, 2.1,3.0,4.0, 4.1, 5.1, 7.1    (mono,stereo,quadro,5.1-surround, 7.1(8channel) surround).
   	Audio architeture: KS, MME, Direct Sound, WASAPI.
3. Volume Control
4. Multiple Installations (supporting say 256 Virtual Cables/Pipelines)
5. Must be near realtime (no delay)
6. This will be a one to one mapping, no need to support for multiple connections mixing.
7. Must appear in Windows Sound Control Panel.
8. Must appear in say GraphEdit, each line in as separate INPUT.
9. Source Code should be properly documented.
10.Sufficient buffering so as to support polling of LINEOUT every 500ms to grab data.
11.Support directshow filter (optional)
12.Must be a valid windows system driver.

Note: A comparable product: http://software.muzychenko.net/eng/vac.html
