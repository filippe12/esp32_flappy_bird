# esp32_flappy_bird
ESP32 flappy bird game

Reused from old project so code might be messy. Reason for why I reused this project was to add more games to the game console I'm building on ESP32.


What you need:

    - ESP32 board

    - OLED display (compatible with u8g2, like an SSD1306)

    - Four buttons

    - ESP-IDF setup (version 3.16 or higher)

    - u8g2 library added as a component
    (You’ll need to modify the CMakeLists.txt path to point to your u8g2 library location. Mine is in oled_test/components outside of this repo, but you can put it wherever you like.)


How to run it

Grab the code:

    git clone https://github.com/filippe12/esp32_flappy_bird.git
    cd esp32_flappy_bird

Make sure you have ESP-IDF set up.

Build and flash:

    idf.py build
    idf.py flash


License:

MIT — do what you want with it!
