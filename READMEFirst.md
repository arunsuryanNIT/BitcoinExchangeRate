# BitcoinExchangeRate 
CPP Project to tell the current bitcoin exchange rate.

### To run it ###
  1. You need curl library.
  2. Install it by running `sudo apt update` and then `sudo apt install libcurl4-openssl-dev` on Linux in terminal.
  3. On Windows [Install Curl](https://curl.haxx.se/dlwiz/?type=lib).

### A Big Note ###
  Compiling Process: once you have installed CURL library then compile it by 
  `g++ --std=c++17 -o Bitcoin Bitcoin.cpp -lcurl` (CPP 17 is necessary) 
  Once compiled then run `./Bitcoin` in terminal.
