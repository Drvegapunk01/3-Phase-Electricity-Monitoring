# 3-Phase-Electricity-Monitoring

This project is a module to monitor the status of a 3-phase electricity supply and record any power outages. The data can be accessed wirelessly.
Currently, the features are limited to detecting the power state only.

This project was inspired by my father’s question about whether it’s possible to create a device that records power outages at the TV transmitter station where he works.

In the PCB, I use two optocouplers on each phase to capture the full-wave signal. Then, I filter the output with a capacitor to obtain a clean DC signal, which is connected to the ESP32’s I/O pins.

