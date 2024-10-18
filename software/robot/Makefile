PORT=/dev/ttyUSB0

deps:
	arduino-cli lib install ESP32Servo

build:
	arduino-cli compile -b esp32:esp32:esp32 -v

upload:
	arduino-cli upload -b esp32:esp32:esp32 -p ${PORT}

serial:
	picocom -b 115200 ${PORT}
