- Checks for latest version of Java 8
  - If not found, asks to download 64-bit Java 8
  - Waits for install before continuing
- Checks for BlissScape.jar
  - If not found, specifies location-specific restriction and asks to download BlissScape before continuing
- Launches BlissScape.jar
- Retains Powershell window with timestamped error-logging

-----------------------------------------------------------------

- Prevents issues caused by Windows’ .jar file association as a zip archive
- Prevents players from being stuck in safe mode due to the client running under JDK
- Prevents client crashes caused by 32-bit Java 8's 256 MB heap limit
