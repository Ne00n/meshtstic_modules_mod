This repository serves a single purpose: to provide source code files for readers of the Meshtastic guideline, allowing them to compile custom firmware for their devices. It includes two simple examples of firmware modifications:

SignalReplyModule – A new, lightweight module that listens for incoming messages containing the text "Ping." Upon receiving such a message, the device retrieves its RSSI/SNR values and sends them back to the sender. This feature helps users assess signal quality between nodes and general network coverage.

Modified RangeTestModule – An enhancement of the existing RangeTestModule. When activated on the sender’s side, it periodically transmits standard positional packets ("loc") along with a direct Google Maps link to its location, making it easier to track node positions.
