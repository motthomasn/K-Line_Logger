# K-Line to SD card logger with RTC

"Hands off" logger for K-Line interface to MicroSD card. Designed specifically for use with a 2005 model Kawasaki KLV1000 or Suzuki DL1000 motorcycle but kept as generic as possible.

Logger is designed to be permanently connected to motorcycle and log whenever ignition is switched on. Power hold capacitors and input voltage detection to allow proper closing of log file.

ECU RAM addresses for logging configured by text configuration file on SD card. Records logged in raw binary in 512byte chunks.

ESP32-C3 Super-mini MCU.

RTC for log file naming.