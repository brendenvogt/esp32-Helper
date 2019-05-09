# Esp32 Install
Get started with the stable version of esp-idf by going to this [Link](https://docs.espressif.com/projects/esp-idf/en/stable/get-started/index.html)

```
cd ~/esp
git clone -b v3.2 --recursive https://github.com/espressif/esp-idf.git
cd ~/esp/esp-idf
git submodule update --init --recursive
```

# Setup PATH to ESP-IDF
```
IDF_PATH
```

# Install the Required Python Packages
```
python -m pip install --user -r $IDF_PATH/requirements.txt

```