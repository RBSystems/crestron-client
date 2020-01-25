# crestron-client

crestron-client is a Python library for connecting to crestron processors and simulating XPanel requests.
This lib is based on [stealthflyers work](https://github.com/stealthflyer/CrestronXPanelApp) who did the entire CIP stuff

## Usage

```python
c = CrestronClient("IP", "PORT")
c.send_digital(81, True) # Join and value digital
c.send_analog(81, 5000) # Join and value analog
```