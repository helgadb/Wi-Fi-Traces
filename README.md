# Wi-Fi-Traces
Files containing Wi-Fi traffic captured in FIBRE testbed. 

The .cap files were sanitized to hide the following information:
- BSSIDs
- Source, destination and trasmitter MAC addresses. (They were replaced by a generic MAC in the sequence of appearance).
- SSIDs (They were replaced by another SSID in the format SSID_ plus a number as they appear in the captures.)
- Manufacturer-specific IE have been removed.
- Malformed packets have been removed.
