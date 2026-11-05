# Hi, I'm Boris Svistunov

[Русская версия](README.ru.md)

I'm a software engineer with nearly eight years of engineering experience in electronics, industrial automation, control systems, and instrumentation. My specialization is engineering software development and integration with industrial equipment.

I develop Python applications for industrial device configuration, diagnostics, production and service workflows, and equipment monitoring. My projects involve desktop interfaces, industrial communication protocols, databases, automated testing, and software packaging.

My engineering background helps me understand how physical equipment operates, troubleshoot hardware–software integration issues, and develop tools that can be validated on real devices.

## Professional Background

I currently work as a Software Engineer at EMIS, focusing on software development and technical support for electricity meters.

My professional experience includes:

- Over five years as an Electronics Engineer at NPO Elektromashina, working on the development and technical support of electronic equipment.
- Inspection, assembly preparation, and technical support of industrial control cabinets and electrical panels based on engineering documentation at Techno-Center.
- Work with flowmeters, pressure sensors, level measurement equipment, and electricity meters at EMIS.
- Development of control and monitoring solutions using OWEN equipment.
- Independently developed EMIS-SYSTEM 500 software for level measurement applications, including control logic using Function Block Diagram (FBD), HMI screen design, and complete technical documentation.
- Collaboration with international equipment manufacturers on firmware troubleshooting, device testing, and technical solutions.
- Functional testing of electricity meters, including communication interfaces, event logs, configuration parameters, and firmware updates.
- Work with DLMS/COSEM, SPODES, and Modbus protocols, including troubleshooting communication between meters, data concentrators, and software systems.
- Participation in preparing technical specifications, coordinating equipment modifications, and validating their implementation with manufacturers.

## Featured Projects

### [HLS Key Control Utility](https://github.com/Sugo174/HLS-Key-Control-Utility)

Desktop application for managing and verifying HLS authentication passwords during electricity meter personalization and servicing, with centralized storage and operation history.

- Writes and verifies HLS passwords on meters over DLMS/COSEM using an optical probe.
- Checks the meter's authentication state after an interrupted write or reset.
- Stores encrypted HLS values, password history, and an operation log in a shared SQL Server database.
- Exports verified personalization batches to Excel.

**Tech Stack** — Python, PySide6, Gurux DLMS, SQL Server, pyodbc, cryptography, XlsxWriter.

### [Smart Meter Configurator](https://github.com/Sugo174/Smart-electric-meter-configurator)

Desktop application for configuring and diagnosing EMIS-ELECTRA 977 DC electricity meters over RS-485, designed to simplify device setup, verification, and servicing.

- Automatically detects the Modbus address, baud rate, and parity.
- Displays live measurements and allows operators to configure daily tariff schedules and pulse output settings.
- Fills in device information from a scanned serial number and synchronizes the meter clock with the PC.
- Reads back written settings to verify that they were applied correctly.
- Provides portable builds for Windows 7 and Windows 10/11, with automated packaging and update checks through GitHub Releases.
- Tested with real single-channel and dual-channel meters.

**Tech Stack** — Python, Tkinter, MinimalModbus, pySerial, PyInstaller.

### [Telegram Push Notification Bot](https://github.com/Sugo174/Telegram-Push-Bot-For-Smart-Electric-Meter)

A server application that receives events from electricity meters over TCP and delivers notifications to subscribers via Telegram.

- Handles packets split across TCP reads and multiple packets received in a single read.
- Decodes meter event flags and stores events in SQLite. Notifications are marked as sent only after a successful response from the Telegram Bot API.
- Supports subscriptions to individual meters and groups, with a separate utility for managing group access.
- Provides a notification archive and an interface in Russian, English, and Simplified Chinese.

**Tech Stack** — Python, asyncio, aiohttp, aiosqlite, SQLite, Telegram Bot API.

### [Cat Home Tasker Bot](https://github.com/Sugo174/Cat-Home-Tasker-TGBot)

Telegram bot for managing shared household chores, with experience points and progression levels.

- Allows users to create a household or join one using an invitation code.
- Supports standard and custom tasks, user profiles, and task completion history.
- Provides an administration panel for managing households and users.
- Stores data in SQLite and supports Russian and English interfaces.

**Tech Stack** — Python, aiogram 3, SQLite.

## Education

### South Ural State University

- **Master's degree** in Automated Electric Drive, 2021.
- **Bachelor's degree** in Automated Electric Drive, 2018.
- **Additional qualification** in English–Russian Technical Translation, 2018.

My master's thesis was part of a four-person Industrial Internet of Things (IIoT) project. The system used equipment tags and augmented reality glasses to display real-time electric motor parameters. I developed a mathematical model of an induction motor in MATLAB for integration into a cloud-based equipment monitoring system.

## Technical Skills

- **Python Development** — desktop applications with PySide6 and Tkinter, asynchronous services with asyncio and aiohttp, Telegram bots with aiogram and the Telegram Bot API.
- **Industrial Communication Protocols** — DLMS/COSEM, SPODES, Modbus RTU/TCP, HART, MQTT.
- **Wired Interfaces and Communication Technologies** — RS-485, optical interfaces for electricity meters, PLC (Power Line Communication).
- **Wireless Communication Technologies** — Bluetooth Low Energy (BLE), Wi-Fi (IEEE 802.11), Zigbee, 868 MHz RF, NB-IoT, LoRaWAN, GSM.
- **Databases and Reporting** — SQL Server via ODBC and pyodbc, SQLite and aiosqlite, Excel exports with XlsxWriter.
- **Security and Diagnostics** — HLS password encryption using `cryptography`, operation logging, and read-back verification of meter configuration changes.
- **Testing and Releases** — automated testing with unittest and GitHub Actions, validation on physical electricity meters, and portable Windows builds with PyInstaller.
- **Electrical and Electronics Engineering** — electrical schematic design, control systems, industrial instrumentation, electric drives, and mathematical modeling in MATLAB.
- **Equipment Testing and Diagnostics** — functional testing of electricity meters, event log verification, communication interface diagnostics, firmware version analysis, firmware update testing, and configuration validation on physical devices.
- **Technical Documentation** — preparation of technical specifications, user manuals, operating instructions, test reports, and coordination of technical requirements with equipment manufacturers.

## Professional Interests

I'm interested in developing my own software applications that interact with real-world hardware, from industrial protocol communication to complete tools for device configuration, diagnostics, and monitoring.

I'm particularly interested in working with SQL databases, designing desktop interfaces, client–server architectures, and automating engineering workflows. I aim to further develop my skills in hardware–software integration, building reliable engineering applications, and processing data collected from connected devices.

I'm open to remote opportunities in engineering software development and industrial automation.

## Languages

- **Russian** — Native.
- **English** — CEFR C2 according to university assessment. Additional qualification in technical translation.

## Contact

- **Email:** [borissvistunov@yahoo.com](mailto:borissvistunov@yahoo.com)
- **Telegram:** [@Sugomak_art](https://t.me/Sugomak_art)
- **GitHub:** [Sugo174](https://github.com/Sugo174)
