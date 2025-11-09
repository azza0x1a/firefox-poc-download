# Chrome Android Download Spoofing POC

## Vulnerability: Download Origin Spoofing
This demonstrates a download spoofing vulnerability in Firefox Android where malicious APK appears to come from trusted origin.

## Files:
- `attacker.apk` - Test APK for PoC
- `exploit.html` - HTML exploit page

## Exploit Flow:
1. User visits malicious page
2. Page opens trusted site (mozilla.org)
3. Download dialog shows trusted origin
4. But file actually comes from attacker server

## Testing:
Visit: yourdomain/yourngrok-free.app


