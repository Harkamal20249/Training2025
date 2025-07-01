# DAY 4 :

# File Compression
It means to compress a file and making file smaller so it takes up less space on your computer.

### **_Why Do We Compress Files?_**
* To save space on your computer
* To send files faster (like in email or WhatsApp)
* To group many files into one (e.g., a ZIP file)

### **_Common Types of Compression_**
* ZIP – Most common (like file.zip)
* RAR – Another type (like file.rar)
* TAR.GZ – Common on Linux systems

### GZIP(GNU zip)
Used to compress files to make file smaller in size.

### **_Syntax in Linux_**
gzip filename

If we want to **UNZIP** the file, use **gunzip**

### **_If not to delete the original file use -k_**
gzip -k filename



# Wild Cards (Globbing)
* Wildcards are special symbols that help you find or work with multiple files without typing every name.
* Think of them like shortcuts when we are dealing with lots of files.

### **_Most Common Wildcards_**

| Wildcard | Meaning                  | Example         | What It Matches              |
| -------- | ------------------------ | --------------- | ---------------------------- |
| *    | Anything                 | *.txt         | All files ending with .txt like notes.txt, file.txt|
| ?    | One character            | file?.txt     | file1.txt, fileA.txt, but not file10.txt          |
| [ ]  | One character from a set | file[1-3].txt | file1.txt, file2.txt, file3.txt                   |


  ### 1. **_*.txt_**


  ### 2. **_?.txt_**

  
  ### 3. **_[ ].txt_**

 
  ### 4. **_Match files that start with fixed letter_**

 
# ASSIGNMENT
---

### Quoting and Escaping Characters

When we type something in the Linux terminal, sometimes our text includes special characters like:
* Space ( )
* Dollar sign ($)
* Asterisk (*)
* Quotes (" or ')
These have special meanings, so if we want the computer to treat them as normal characters, we need to use quoting or escaping.

### **_Escaping_**
Escaping means protecting a character so the terminal doesn't give it a special meaning. Use backslash (\) for escaping.


### **_Quoting_**
Quoting is putting your text inside quotes so special characters don’t get a special meaning.

  ### **_1. Single Quotes ' '_**
  * Treat everything inside as plain text.
  * Nothing gets special meaning.



  ### **_2. Double Quotes " "_**
  * Treat most things as plain text, but variables and commands still work.

 
  ---

  # Hardware Parts

  ### **_1. Basic Computer Architecture_**

  | Term                  | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **PC (Hardware)**     | Physical components of a computer.                     |
  | **System Software**   | OS installed on hardware (e.g., Windows, Ubuntu).      |
  | **Application Software** | Installed on OS (e.g., MS Word, Chrome, VLC).       |
      
  ### **_2. CPU & Internal Components_**
      
  | Component             | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **CPU**               | Central Processing Unit; brain of the computer.        |
  | **Motherboard**       | Main circuit board connecting all components.          |
  | **RAM**               | Volatile memory; data lost on shutdown.                |
  | **ROM**               | Non-volatile memory; stores firmware.                  |
  | **Cache**             | Very fast memory between CPU and RAM.                  |
  | **Registers**         | Small, fast memory inside CPU for temporary data.      |
  | **Control Unit (CU)** | Directs data flow and operations in CPU.               |
  | **ALU**               | Performs calculations and logic.                       |
  | **Clock**             | Synchronizes CPU operations using electrical pulses.   |
  | **Transistors**       | Basic switching units used in processing.              |
  | **Chipset**           | Controls communication; Northbridge and Southbridge.   |
  | **CPU Socket**        | Slot where CPU is mounted; fan usually above it.       |
      
  ### **_3. Storage Devices_**
      
  | Component             | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **Hard Disk (HDD/SSD)** | Permanent storage for OS, apps, and files.           |
  | **RAM**               | Temporary, fast memory used during system operation.   |
  | **Cache**             | Small, faster memory for urgent data access.           |
  | **Floppy Disk**       | Old magnetic storage medium (now obsolete).            |
  | **CD/DVD**            | Optical media used to read/write data.                 |
  | **BD (Blu-ray Disk)** | High-capacity optical disk for HD media and backups.   |
      
  ### **_4. Power & Booting_**
      
  | Component             | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **Power Supply (SMPS)** | Converts AC to DC; supplies power to components.     |
  | **UPS**               | Battery backup for power outages.                      |
  | **CMOS Battery**      | Maintains BIOS settings and system time.               |
  | **Boot Process**      | Power on → ROM → Bootstrap Loader → OS loads in RAM.   |
      
  ### **_5. Input/Output & Display_**
      
  | Component             | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **Monitor**           | Output device to display visuals.                      |
  | **HDMI Port**         | High-definition video output for projectors/displays.  |
  | **VGA Port**          | Older analog video output; needs converter for HDMI.   |
  | **Display Adapter**   | Processes and displays graphics (GPU).                 |
  | **TV Tuner Adapter**  | Enables TV signal input to PC.                         |
      
  ### **_6. Networking & Communication_**
      
  | Component             | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **LAN (Local Area Network)** | Network connecting nearby computers.            |
  | **Modem**             | Converts digital ↔ analog signals for internet.        |
  | **LAN Card / NIC**    | Allows PC to connect to network via cable.             |
      
  ### **_7. Other Components & Concepts_**
      
  | Component             | Definition                                             |
  |-----------------------|--------------------------------------------------------|
  | **Drivers**           | Software that lets OS interact with hardware.          |
  | **BIOS Chip**         | Firmware chip that starts hardware and loads OS.       |
  | **Peripheral Devices**| External devices like mouse, keyboard, printer, etc.   |
  | **PCI Slots**         | Expansion slots for adding cards (e.g., sound, LAN).   |
  | **Expansion Slots**   | Slots for adding extra hardware (graphics, TV cards).  |
  | **SATA Ports**        | Connect HDDs and SSDs to motherboard.                  |
  | **Beep Sound**        | POST error codes (e.g., via speaker/copper coil).      |
  | **Cooling System**    | Fans or heat sinks to prevent overheating.             |
  | **Configuration**     | System specs: RAM, CPU speed, storage, brand, etc.     |
