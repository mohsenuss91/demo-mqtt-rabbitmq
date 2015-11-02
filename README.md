# demo-mqtt-rabbitmq

MQTT with RabbitMQ plugin (no qos 2 supported)

## initial chef cookbook

```bash
git submodule init
git submodule update
```

## boot server

```bash
vagrant up
```

## script 

```bash
pip install -r requirements.txt
python mqtt.py
```

### Management plugin (guest/guest)

```
http://localhost:15672
```
