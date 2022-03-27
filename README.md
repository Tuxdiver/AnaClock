Video: [![Video of the analog clock in action]({Media/anaclock.png})]({Media/anaclock.mov} "Video")
Compile and run:

```docker run --rm -v "${PWD}":/config --device=/dev/ttyUSB0 -it esphome/esphome run anaclock_lolin.yaml```
