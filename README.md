# mongoose-os-m6315

Mongoose OS firmware for M6315

https://github.com/ushijimamit/pppos-m6315

mos build --arch esp32 --verbose --clean --local

mos flash build/fw.zip --esp-erase-chip --catch-core-dumps no
