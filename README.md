# GD-Android32-Class-Members-Importer
A Script to move cocos2d &amp; Geometry Class members and their accurate offsets and vtables to Ghidra &amp; Possibly IDA

# The Problems at hand
- The [Geode Bindings](https://github.com/geode-sdk/bindings) __Do Not Provide cocos2d class members__ which makes the readability of code inside of ghidra somewhat difficult
- Configuring these class members by hand can be tedious work and are prone to human error even one mistake requires too many hours to fix just a handful of cocos2d class members


My Goals with this library are simple
- Provide and accurate libcocos2d broma file along with padding for filling out fields
- Provide readability and accurate class information
- Fill all subclass members where they go as best and as accurate possible. 
- Provide vtables when RTII is unavalible
- To make it easier than ever to reverse engineer geometry dash on most android 32 bit platforms
- Make the script and broma files open source so people can help me with fixing mistakes.
