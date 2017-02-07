---
-api-type: winrt property
---
 Hardware control: The Request-to-Send (RTS) line is set to false when the receiver's buffer is full. This indicates to the sender that it must stop sending data. When the buffer is able to hold data, the RTS line is set to true that indicates to the send that it is now ready to receive data again.
 Software control: The receiver sends an Xoff control code to the sender to stop transmission of data. When the receiver is ready, it sends the Xon code and the sender resumes data transmission.