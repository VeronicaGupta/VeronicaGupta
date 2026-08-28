# Parnika Gupta

**Embedded firmware engineer** — 3+ years of full-time professional experience in C/C++/Python across bare-metal, RTOS, and Embedded Linux. Security-critical crypto firmware, EtherCAT-certified industrial systems, and IoT platforms built from scratch as a founding engineer. I take features from hardware bring-up through drivers, protocols, and compliance to ship.

MS EE @ NYU Tandon (May 2026) · **Open to embedded / firmware roles**

[Email](mailto:pg2825@nyu.edu) · [LinkedIn](https://linkedin.com/in/parnikagupta9) · [Portfolio](https://sites.google.com/nyu.edu/parnika-gupta)

#### ⚡ Skills

[![My Skills](https://skillicons.dev/icons?i=c,cpp,py,bash,ts,rust,matlab,linux,qt,cmake,docker,git,github,aws&theme=light&perline=7)](https://skillicons.dev)

- **Languages** — Embedded C, C++, Python, Shell, Structured Text (PLC), Assembly, TypeScript, MATLAB, LaTeX
- **Silicon & boards** — STM32, ESP32, ARM Cortex, Xilinx FPGA, VEGA SoC (RISC-V), Raspberry Pi, NanoPi
- **OS & kernel** — RTOS, Embedded Linux, Yocto, bootloaders, secure boot, kernel modules, POSIX, DMA
- **Protocols** — EtherCAT, SPI, I2C, UART, CAN, USB, Ethernet, MQTT, BLE, WiFi, GSM, TCP, ADC/DAC, IPC
- **Tools** — TwinCAT, EtherCAT CTT, KPA Studio, Cadence Virtuoso, Proteus, JTAG debuggers, oscilloscope, logic/spectrum/network analyzers, Docker, CMake, JIRA
- **Domains** — embedded systems, signal processing, hardware bring-up and testing, conformance (protocol / safety / EMC / RoHS), automation, IoT, control systems

---

## Education

- **MS Electrical Engineering**, NYU Tandon — *Sept 2024 – May 2026*
  - Embedded Systems, Control Systems, DSP, Analog Circuit Design, Interactive Medical Robotics, Neuro & Physiological Signal Processing, Image/Video Processing with ML, Probability and Statistics
- **B.Tech Electronics & Communication**, Banasthali University — *July 2016 – July 2020*
  - Microcontrollers, Digital Electronics, Computer Architecture, Communication Networks, Probability

## Experience

- **Hypertherm Associates** · Project Associate (Intern), USA · *May – Aug 2025*
  - **Task** — Test how the plasma cutter's 32-bit MCU talks to the CNC controls over EtherCAT. Measured latency on the critical process data, found where hardware and software were dropping or delaying messages, and ran EtherCAT conformance certification with the official CTT tool and KPA Studio statistics, recreating real industry scenarios.
  - **Skills** — Embedded C (Hilscher), Structured Text PLC, TwinCAT, EtherCAT, CTT, KPA Studio, latency measurement, automated regression testing

- **Faucet Labs (Cypherock)** · Embedded Engineer / Team Lead, India · *Dec 2023 – Aug 2024*
  - **Task** — Build a way to hand a hardware wallet over to an heir without the seed ever leaving the device — a symmetric-key inheritance transaction architecture in STM32 firmware. Added Starknet and Bittensor transaction signing, and led the hardware team through client issues, bug fixes, and feature integration.
  - **Skills** — Embedded C (STM32), TypeScript, Python, symmetric-key cryptography, transaction signing, code review, [GSoC](https://github.com/Cypherock/gsoc) mentoring

- **Kimbal Tech** · Automation Engineer (Consultant), India · *Nov – Dec 2023*
  - **Task** — Write a simulator that runs a three-phase smart meter through 12 validation phases as a state machine, with time-locked pass/fail output, so bad units get caught on the line instead of in the field. Defect rate fell 20%.
  - **Skills** — C++, multi-stage state machines, time-locked validation, unit testing, automated diagnostic feedback

- **Avrio Energy** · Embedded Developer & Founding Member, India · *Oct 2020 – Oct 2023*
  - **Task** — Founding engineer on an AI energy meter, sensor to cloud. Brought up the board, wrote the drivers, built the Yocto/ARM Linux image, and moved binary packets over SPI, UART and Ethernet into an MQTT pipeline for remote monitoring and OTA updates — 1% voltage and current accuracy at 1s latency, with a static config flow reworked into a parametrized calibration file. Also traced EMC and safety compliance failures back to high-frequency noise in the PCB and schematic, automated sensor-driven HVAC switching (10% warehouse energy saved), and set up procurement, manufacturing and QC (throughput doubled, 100% installation success).
  - **Skills** — Embedded C (ESP32, Xilinx), C++, Python, Yocto, ARM Linux, SPI, UART, Ethernet, MQTT, OTA updates, edge ML micro-services, EMC & safety compliance RCA, Grafana, documentation, procurement, QC

- **Gaia Smart Cities** · Project Associate (Intern), India · *Jan – Oct 2020*
  - **Task** — Commission IoT gateways in bulk instead of one technician per unit. STM32 firmware plus a PyQt desktop tool that drives the modem over AT commands, checks signal health, parses logs, and batches the tests. Deployed across 300+ airports; end-to-end test time fell 5×.
  - **Skills** — Embedded C++, RTOS, STM32, Python, PyQt5, Qt, GSM, AT commands, USB-serial, log parsing, batch test automation

- *Also:* Engineer at Accenture (Data Management Platform, 10 months) · NYU Course Assistant, Fundamentals of Electronics I & II

## Projects

- **[Linux Edge ML Energy Analytics](https://github.com/VeronicaGupta/Linux_Edge_ML_Energy_Analytics)** · *Avrio Energy*
  - **Task** — Work out which appliance just switched on or off by watching only the whole-home current, with no sensor per device. NILM inference runs on the meter itself — a memory- and CPU-constrained FPGA — at 90% accuracy, with remote retraining that needs no reprogramming, live cloud streaming, and a one-command factory reset.
  - **Skills** — Embedded Linux, VEGA SoC (RISC-V), Xilinx FPGA, secure boot, SPI/I2C drivers, multithreading, thread-safe producer-consumer queues, state machines, DSP, ADE register calibration, MQTT/Mosquitto, SSL certificates, TinyDB, InfluxDB, Grafana, shell scripting

- **[RTOS EtherCAT Performance Analysis](https://github.com/VeronicaGupta/RTOS_EtherCAT_Perfomance_Analysis)** · *Hypertherm*
  - **Task** — Measure latency between the plasma cutter MCU and the CNC controls, and leave behind a Structured Text PLC routine the team can rerun as a standard internal controller test.
  - **Skills** — Embedded C, Structured Text, TwinCAT, RTOS, EtherCAT, SPI, UART, unit/integration/system testing, automated regression testing

- **[RTOS Motion Processing](https://github.com/VeronicaGupta/RTOS_Motion_Processing_for_Pattern_Recognition)** · *NYU Embedded Systems*
  - **Task** — Gesture unlock. Sample the gyro over SPI on interrupt, smooth it with a moving-average FIR, save the sequence to flash, then score a new gesture against it with DTW — unlock on a match, stay locked on anything else, with LCD feedback for success, failure and loading.
  - **Skills** — Embedded C++, STM32, interrupt-driven SPI, IMU sensors, event queues, state machines, FIR filtering, DTW matching, flash file I/O, LCD driver, Teleplot

- **[Linux Cryptographic Session](https://github.com/VeronicaGupta/Linux_Cryptographic_Session_Encrypt_Decrypt)** · *Cypherock*
  - **Task** — Set up an encrypted channel between client and server starting from nothing but a shared BIP39 mnemonic: derive identity keys down BIP32 paths, authenticate the ephemeral ECDH keys with ECDSA so both sides are verified, then derive an AES session key for messaging.
  - **Skills** — Python, ECDH, secp256k1, BIP32/BIP39 derivation, ECDSA, AES-256, point compression, client-server security design

- **Linux Kernel Message Queue**
  - **Task** — A character-device message queue inside the Linux kernel so several user-space producers and consumers can pass messages safely — bounded ring buffer, blocking read/write, no race conditions, no unbounded memory growth, no busy-waiting.
  - **Skills** — Linux kernel module, character device, circular buffer, mutex/semaphore synchronization, blocking I/O, Makefile build flow, insmod/rmmod, dmesg, multithreaded producer-consumer validation

- **[Wide-band Transimpedance Amplifier](https://github.com/VeronicaGupta/Wide-band-Transimpedance-Amplifier)** · *NYU*
  - **Task** — Turn the tiny current out of a photodiode into a usable voltage as the front end for an optical sensor. Transistor-level design — four CMOS stages plus a differential stage, tuned for noise. >5 GHz bandwidth, 74 dB gain.
  - **Skills** — Transistor-level CMOS design, differential topology, noise tuning, Cadence Virtuoso

- **[Melanoma Triage](https://github.com/VeronicaGupta/melonoma-detection)** · *NYU*
  - **Task** — Flag which skin lesions need a biopsy, from the image plus patient metadata. Built for the pre-biopsy case where missing a malignancy costs far more than a false alarm, on data with extreme class imbalance and non-dermoscopic image quality.
  - **Skills** — Python, class-imbalance handling, real + synthetic training data, image and metadata model ensembling, partial-AUC evaluation above a minimum TPR threshold

- **[Prostate MRI Segmentation](https://github.com/Shrey12202/Prostate-MRI-Segmentation)** · *NYU*
  - **Task** — Segment the prostate on MRI without a human drawing the box first. Fine-tuned MedSAM2 against a U-Net baseline, with a learned bounding-box predictor (BoxNet) supplying the prompt at inference — cuts contouring time and inter-reader variability.
  - **Skills** — MedSAM2 fine-tuning, U-Net, BoxNet bounding-box prediction, Dice evaluation, Prostate158 dataset

More on the [portfolio site](https://sites.google.com/nyu.edu/parnika-gupta), with reports, posters, and demo videos.

## Achievements

- **[Swadeshi Microprocessor Challenge](https://shakti.org.in/sp2020-shakti.html) 2021** — $30,000 prize, national. Single-sensor appliance detector at 90% accuracy on a new FPGA stack; demoed to India's Minister of Electronics & IT. [Video](https://youtu.be/csK1fTdUoUE)
- **[ETHDenver Hackathon](https://www.starknet.io/blog/starknet-ethdenver-hacker-house/) 2024** — $25,000 grant for a Starknet signing PoC built on hardware in 3 days.
- **[Carbon Zero Challenge](https://czeroc.in/gallery/shortlisted-teams-2022/) 2022** — $6,000 grant from IIT Madras, plus the challenge's Women's Day Honor.
- **SWE Conference 2025** — sponsored by NYU. **Science Quiz 2019** — 2nd rank, university.

## Things I Like to Do

Singing, swimming, and martial arts — the things that keep the desk hours honest. I volunteer with [Heartfulness](https://www.linkedin.com/company/heartfulness) (meditation) and am a member of [WomenAdoreTech](https://www.linkedin.com/company/womenadoretech). Off-hours reading is mostly science, psychology, and history — good places to steal first-principles ideas from.
