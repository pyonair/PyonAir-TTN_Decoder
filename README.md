# PyonAir-TTN_Decoder

Decoder for decoding LoRa messages sent by the PyonAir.

Place the contents of decoder.js to Application, Payload Formats on The Things Network.

The first version deals with TPP, TP, PP, P, T and G formats, where T stands for Temperature and Humidity sensor, P stands for Particulate Matter sensor, and G stands for GPS.

If the payload format is changed on the PyonAir, this decoder should be updated, version 2 released, and copied to TTN.

The code was adapted from:
https://github.com/pgriess/node-jspack
