this is notes mostly for me but u can use this

# GPIO
- **use raw BCM pinouts** - gpiozero uses raw BCM pinouts, and so does FastIO
- gpiozero has 100khz polling rate; FastIO has 2mhz polling rate (tested with `./debug/gzmaxio.py` and `./core/pio/fastio.py`, respectively)

# spi
add `dtoverlay=spi1-2cs` to `/boot/config.txt`  

6/19/24 pls get python3-dev using apt