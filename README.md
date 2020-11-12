# IOT for micro:bit in python

A package for the to connect BBC microbit to an MQTT broker in the cloud and send a message to a telegram bot.

![logo](https://github.com/mimidbe/IOT-for-micro-bit-in-python/blob/main/images/schema.png)
![logo](https://github.com/mimidbe/IOT-for-micro-bit-in-python/blob/main/images/circuit.png)


connect_wifi(self, yourSSID,yourPASSWORD)

connect_iot_cloud(server,port,user,password)

subscribe(topicName)

publish(topicName, message)

send_telegram(BotApiKey, MyChannelName, message)
