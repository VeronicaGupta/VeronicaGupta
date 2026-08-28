# Parnika Gupta

**Embedded firmware engineer** — ~5 years in C/C++ across bare-metal, RTOS, and Embedded Linux. Security-critical crypto firmware, EtherCAT-certified industrial systems, and IoT platforms built from scratch as a founding engineer. I take features from hardware bring-up through drivers, protocols, and compliance to ship.

MS EE @ NYU Tandon (May 2026) · New York · **Open to embedded / firmware roles**

[Email](mailto:pg2825@nyu.edu) · [LinkedIn](https://linkedin.com/in/parnikagupta9) · [Portfolio](https://sites.google.com/nyu.edu/parnika-gupta)

**Stack** — 💻 C, C++, Embedded C, Python, Structured Text · 🔩 STM32, ESP32, ARM Cortex, Xilinx FPGA, VEGA (RISC-V) · 🐧 RTOS, Embedded Linux, Yocto, bootloaders, kernel modules · 🔌 EtherCAT, SPI, I2C, UART, CAN, MQTT, BLE, GSM · 🧰 TwinCAT, CTT/KPA, Cadence Virtuoso, logic analyzers, JTAG

<sub>💻 languages · 🔩 silicon & boards · 🐧 OS & kernel · 🔌 protocols · ⚙️ architecture · 🔐 security · 📊 signals & data · 🧪 test · 🧰 tools · ✅ compliance · 👥 people</sub>

---

## Education

- **MS Electrical Engineering**, NYU Tandon — *Sept 2024 – May 2026*. Embedded Systems, Control Systems, DSP, Analog Circuit Design, Medical Robotics, Neuro & Physiological Signal Processing, Image/Video Processing with ML.
- **B.Tech Electronics & Communication**, Banasthali University — *July 2016 – July 2020*.

## Experience

**Hypertherm Associates** · Project Associate (Intern), USA · *May – Aug 2025*
**Task** — Find and quantify communication faults between a plasma cutter's 32-bit MCU and CNC controls, and certify the link's EtherCAT conformance.
**Skills** — 💻 Embedded C (Hilscher), Structured Text PLC · 🔌 EtherCAT · 🧰 TwinCAT, CTT, KPA Studio · 🧪 latency measurement, automated regression testing

**Faucet Labs (Cypherock)** · Embedded Engineer / Team Lead, India · *Dec 2023 – Aug 2024*
**Task** — Make hardware-wallet ownership transferable without ever exposing the seed, extend chain support, and lead the hardware team.
**Skills** — 💻 Embedded C (STM32), TypeScript, Python · 🔐 symmetric-key cryptography, Starknet & Bittensor transaction signing · 👥 code review, [GSoC](https://github.com/Cypherock/gsoc) mentoring

**Kimbal Tech** · Automation Engineer (Consultant), India · *Nov – Dec 2023*
**Task** — Catch defects on a three-phase smart-meter production line before units ship; defect rate fell 20%.
**Skills** — 💻 C++ · ⚙️ multi-stage state machines · 🧪 time-locked validation, automated diagnostic feedback

**Avrio Energy** · Embedded Developer & Founding Member, India · *Oct 2020 – Oct 2023*
**Task** — Build an AI energy-metering product from nothing — sensor to cloud — plus the manufacturing behind it. 1% V/I accuracy at 1s latency, 10% warehouse energy saved, 100% installation success, throughput doubled.
**Skills** — 💻 Embedded C (ESP32, Xilinx), C++, Python · 🐧 Yocto / ARM Linux · 🔌 SPI, UART, Ethernet, MQTT, OTA updates · 📊 Grafana · ✅ EMC & safety compliance RCA · 👥 documentation, procurement, QC

**Gaia Smart Cities** · Project Associate (Intern), India · *Jan – Oct 2020*
**Task** — Commission IoT gateways at airport scale without a technician debugging each one; shipped to 300+ airports, testing 5× faster.
**Skills** — 💻 Embedded C++, Python / PyQt5 · 🔩 STM32, RTOS · 🔌 GSM / AT commands · 🧪 log parsing, batch test automation

*Also:* Engineer at Accenture (Data Management Platform, 10 months) · NYU Course Assistant, Fundamentals of Electronics I & II.

## Projects

**[Linux Edge ML Energy Analytics](https://github.com/VeronicaGupta/Linux_Edge_ML_Energy_Analytics)** · *Avrio Energy*
**Task** — Tell which appliance switched on or off from a single whole-home sensor, inferring on the meter itself. 90% accuracy on a memory- and CPU-constrained FPGA, retrainable remotely without reflashing.
**Skills** — 🐧 Embedded Linux, secure boot, shell scripting · 🔩 VEGA SoC (RISC-V), Xilinx FPGA · 🔌 SPI/I2C drivers, MQTT · ⚙️ multithreading, producer-consumer queues · 📊 InfluxDB, Grafana

**[RTOS EtherCAT Performance Analysis](https://github.com/VeronicaGupta/RTOS_EtherCAT_Perfomance_Analysis)** · *Hypertherm*
**Task** — Measure latency between the plasma cutter MCU and CNC controls, and leave the team a repeatable PLC method for standardized controller testing.
**Skills** — 💻 Embedded C, Structured Text / TwinCAT · 🔩 RTOS · 🔌 EtherCAT, SPI, UART · 🧪 unit/integration/system testing

**[RTOS Motion Processing](https://github.com/VeronicaGupta/RTOS_Motion_Processing_for_Pattern_Recognition)** · *NYU Embedded Systems*
**Task** — Unlock a device by gesture: record a gyroscope sequence to flash, match later attempts against it, stay locked on mismatch.
**Skills** — 💻 Embedded C++ · 🔩 STM32, IMU, interrupt-driven SPI · ⚙️ event queues, state machines · 📊 moving-average FIR, DTW matching · 🧰 flash file I/O, LCD feedback, Teleplot

**[Linux Cryptographic Session](https://github.com/VeronicaGupta/Linux_Cryptographic_Session_Encrypt_Decrypt)** · *Cypherock*
**Task** — Derive a mutually authenticated encrypted channel between client and server from nothing but a shared BIP39 mnemonic.
**Skills** — 💻 Python · 🔐 ECDH, secp256k1, BIP32/39 derivation, ECDSA, AES-256, point compression · ⚙️ client-server security design

**Linux Kernel Message Queue**
**Task** — Let many user-space producers and consumers exchange messages through the kernel without races, unbounded memory growth, or busy-waiting.
**Skills** — 🐧 Linux kernel module, character device, insmod/rmmod, dmesg · ⚙️ circular buffer, mutex/semaphore synchronization, blocking I/O · 🧰 Makefile build flow · 🧪 multithreaded validation

**[Wide-band Transimpedance Amplifier](https://github.com/VeronicaGupta/Wide-band-Transimpedance-Amplifier)** · *NYU*
**Task** — Turn weak photodiode current into usable voltage as a low-noise optical front end — >5 GHz bandwidth, 74 dB gain.
**Skills** — 🔩 transistor-level CMOS design, 4-stage + differential topology, noise tuning · 🧰 Cadence Virtuoso

**[Melanoma Triage](https://github.com/VeronicaGupta/melonoma-detection)** · *NYU*
**Task** — Triage melanoma risk from lesion images and metadata before biopsy, where missed malignancies are the costly error.
**Skills** — 💻 Python · 📊 extreme class-imbalance handling, real + synthetic training data, image/metadata ensembling · 🧪 sensitivity-focused partial-AUC evaluation

**[Prostate MRI Segmentation](https://github.com/Shrey12202/Prostate-MRI-Segmentation)** · *NYU*
**Task** — Segment prostate anatomy on Prostate158 with no manual prompts at inference, cutting contouring time and inter-reader variability.
**Skills** — 📊 MedSAM2 fine-tuning, U-Net, learned bounding-box predictor (BoxNet) · 🧪 Dice evaluation

More on the [portfolio site](https://sites.google.com/nyu.edu/parnika-gupta), with reports, posters, and demo videos.

## Achievements

- **[Swadeshi Microprocessor Challenge](https://shakti.org.in/sp2020-shakti.html) 2021** — $30,000 prize, national. Single-sensor appliance detector at 90% accuracy on a new FPGA stack; demoed to India's Minister of Electronics & IT. [Video](https://youtu.be/csK1fTdUoUE)
- **[ETHDenver Hackathon](https://www.starknet.io/blog/starknet-ethdenver-hacker-house/) 2024** — $25,000 grant for a Starknet signing PoC built on hardware in 3 days.
- **[Carbon Zero Challenge](https://czeroc.in/gallery/shortlisted-teams-2022/) 2022** — $6,000 grant from IIT Madras, plus the challenge's Women's Day Honor.
- **SWE Conference 2025** — sponsored by NYU. **Science Quiz 2019** — 2nd rank, university.

## Things I Like to Do

Singing, swimming, and martial arts — the things that keep the desk hours honest. I volunteer with [Heartfulness](https://www.linkedin.com/company/heartfulness) (meditation) and am a member of [WomenAdoreTech](https://www.linkedin.com/company/womenadoretech). Off-hours reading is mostly science, psychology, and history — good places to steal first-principles ideas from.
