Skriptik can scan for Routers/Servers that use Mikrotik OS.
It reads a directory based on an IP list. A request is made at port 23 which is also used by Mikrotik to be configured with CLI. After the request is made, there's a response should a Mikrotik OS be found in the device. The scanner script checks to see if there's a Mikrotik version existing. At the end of the scan the result is saved in order to review the scanning process.