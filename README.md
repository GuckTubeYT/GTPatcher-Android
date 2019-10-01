# GTPatcher-Android
Tool for patching Growtopia apk ip address for private servers.

# Notes
- After patching, you have to sign the apk in order to install it on android.
- Please do not create issues about no sound playing. There is no way to fix this at it's current state. The cause could be a fake signature that some apps use. I will look forward to it.
- Tested only with ip addresses that are 14 characters in length. It should also work on less, but not more.
- Tested on Eclipse IDE.
# Usage
Please use the following command for patching:

```java -jar GrowtopiaPatcher.jar <apk file> <new ip address> [alternative ip address]```
