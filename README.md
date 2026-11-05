# Hi, I'm Boris Svistunov

[Русская версия](README.ru.md)

I am a software engineer with nearly eight years of experience in electrical engineering, industrial automation, control systems, and instrumentation.

I develop Python applications for industrial device configuration, diagnostics, production and service workflows, and equipment monitoring. My projects combine desktop interfaces, industrial communication protocols, databases, automated testing, and software deployment.

My engineering background helps me understand how physical equipment operates, investigate hardware-software integration issues, and develop reliable tools that can be tested on real devices.

## Professional Background

I currently work as a Software Engineer at EMIS, where I focus on the software side and technical support of smart electricity meters.

My industrial experience includes:

- Five years in industrial automation at NPO Elektromashina.
- Design of custom control cabinets for industrial enterprises at Techno-Center.
- Work with flowmeters, pressure sensors, level measurement equipment, and smart electricity meters at EMIS.
- Development of control and monitoring solutions using OWEN equipment.
- Independently developed the EMIS-SYSTEM 500 software for level measurement applications, including control logic using Function Block Diagram (FBD), HMI screen design, and complete technical documentation.
- Software development and technical support for smart electricity meters.
- Technical communication with international equipment manufacturers, including firmware troubleshooting, device testing, and coordination of technical solutions.
- Investigation of hardware-software integration issues and validation of device behavior using physical test equipment.

## Featured Projects

### [HLS Key Control Utility](https://github.com/Sugo174/HLS-Key-Control-Utility)

Desktop application for managing and verifying HLS authentication passwords during electricity meter personalization and servicing, with centralized storage and operation history.

- Writes and verifies HLS passwords on meters over DLMS/COSEM using an optical probe.
- Checks the meter's authentication state after an interrupted write or reset.
- Stores encrypted HLS values, password history, and an operation journal in a shared SQL Server registry.
- Exports confirmed personalization batches to Excel.

**Technology:** Python, PySide6, Gurux DLMS, SQL Server, pyodbc, cryptography, XlsxWriter

### [Smart Meter Configurator](https://github.com/Sugo174/Smart-electric-meter-configurator)

Desktop application for configuring and diagnosing EMIS-ELECTRA 977 DC electricity meters over RS-485, designed to simplify device setup, verification, and servicing.

- Automatically detects the Modbus address, baud rate, and parity.
- Displays live measurements and lets operators configure daily tariff schedules and pulse output settings.
- Fills in device information from a scanned serial number and synchronizes the meter clock with the PC.
- Reads back written settings to verify that they were applied.
- Provides portable builds for Windows 7 and Windows 10/11, with automated packaging and update checks through GitHub Releases.
- Tested with real single-channel and dual-channel meters.

**Built with** Python, Tkinter, MinimalModbus, pySerial, and PyInstaller.

### [Telegram Push Notification Bot](https://github.com/Sugo174/Telegram-Push-Bot-For-Smart-Electric-Meter)

Receives events from electricity meters over TCP and delivers notifications to subscribers in Telegram.

- Handles packets split across TCP reads and multiple packets received in a single read.
- Decodes meter event flags, stores events in SQLite, and marks notifications as sent only after Telegram confirms delivery.
- Supports subscriptions to individual meters and groups, with a separate utility for managing group access.
- Provides a notification archive and a Telegram interface in Russian, English, and Simplified Chinese.

**Built with** Python, asyncio, aiohttp, aiosqlite, SQLite, and the Telegram Bot API.

### [Cat Home Tasker Bot](https://github.com/Sugo174/Cat-Home-Tasker-TGBot)

Telegram bot for sharing household chores and tracking progress through experience points and levels.

- Lets users create a household or join one with an invitation code.
- Supports standard and custom tasks, user profiles, and task completion history.
- Provides an administration panel for managing households and users.
- Stores household data in SQLite and supports Russian and English interfaces.

**Built with** Python, aiogram 3, and SQLite.

## Education

### South Ural State University

- **Master's degree in Automated Electric Drive**, 2021
- **Higher education in Automated Electric Drive**, 2018
- **Additional qualification:** English–Russian Translator in Technical Communication
- English proficiency assessed at **CEFR C2** through university testing

My master's project was developed as part of a four-person Industrial Internet of Things project. The system used equipment tags and augmented-reality glasses to display live electric motor parameters.

My part of the project was a mathematical model of an induction motor designed for integration into cloud computing workflows. The model was developed in MATLAB.

## Technical Skills

- **Python development** — desktop applications with PySide6 and Tkinter, asynchronous services with asyncio and aiohttp, and Telegram bots with aiogram and the Telegram Bot API.
- **Industrial and IoT protocols: Modbus RTU/TCP, DLMS/COSEM, SPODES, HART, MQTT.
- **Wired interfaces and communication technologies: RS-485, PLC (Power Line Communication).
- **Wireless communication technologies: Bluetooth Low Energy (BLE), Wi-Fi (IEEE 802.11), Zigbee, 868 MHz RF, NB-IoT, GSM.
- **Databases and reporting** — SQL Server via ODBC and pyodbc, SQLite and aiosqlite, and Excel exports with XlsxWriter.
- **Security and diagnostics** — credential encryption with `cryptography`, operation logging, and verification of meter settings after writes.
- **Testing and releases** — automated tests with unittest and GitHub Actions, testing with physical meters, and portable Windows builds with PyInstaller.
- **Engineering** — electric drives, industrial instrumentation, control cabinet design, and mathematical modelling in MATLAB.

## Professional Interests

I am open to remote roles in software engineering and industrial automation, especially work involving equipment communication, diagnostics, or software for commissioning and service teams.

I build and maintain Python tools that connect to physical devices, process operational data, and help operators verify the results of their work. I am continuing to improve how I test device workflows, diagnose communication failures, and package and document releases.

## Languages

- **Russian:** Native
- **English:** CEFR C2 according to university assessment; qualified in technical translation

## Contact

- **Email:** [borissvistunov@yahoo.com](mailto:borissvistunov@yahoo.com)
- **Telegram:** [@Sugomak_art](https://t.me/Sugomak_art)
- **GitHub:** [Sugo174](https://github.com/Sugo174)
