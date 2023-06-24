# MAVLink

## Prerequisites

```
sudo apt-get install python-lxml
```

## Code generation 

```
git clone https://github.com/ArduPilot/pymavlink.git
python3 ./pymavlink/tools/mavgen.py --lang=C --wire-protocol=2.0 --output=generated/include/mavlink/v2.0 message_definitions/common.xml
```
