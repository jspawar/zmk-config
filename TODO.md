1. Is it fine to create the new directory under `boards/shields` when nothing was there before? should it go under `config/boards/shields` like beekeeb person did?
    * https://blog.beekeeb.jp/zmk-dongle-support/
2. The beekeeb blog uses `default_transform` in the overlay instead of `physical_layout0` as the ZMK docs suggest, is that fine?
3. The Prospector ZMK module states that the main branch doesn't support Zephyr 4.1, switch to their dev branch which supports it or pin Zephyr version somehow?
4. Is `seeeduino_xiao_ble` even the right board for the Prospector from beekeeb?
