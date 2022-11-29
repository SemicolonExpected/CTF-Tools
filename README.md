# CTF-Tools
## Misc
- CyberChef
- MOSINT
- Maigret `maigret <username> -a`
- NEXFIL `python3 nexfil.py -u <username>`
- [RSACTFTool](https://github.com/RsaCtfTool/RsaCtfTool) `python RsaCtfTool -n <n> -e <e> --uncipher <c>`
## Ip Location Finder
- https://tools.keycdn.com/geo
## Magnetic Card Decoder
- [Magstripper](https://sourceforge.net/projects/magstripper/) decodes magnetic cards given a waveform
## Password Cracking
- [Hashcat sample rules](https://github.com/hashcat/hashcat/tree/master/rules) see leetspeak rule OwO
- [THE ONE RULE](https://github.com/NotSoSecure/password_cracking_rules) for hashcat
- [Another ONE RULE](https://github.com/stealthsploit/Optimised-hashcat-Rule)
## Scanning and Recon
- dirbuster
- `nc <host> <port>`
- `nc -u <host> <port>`
- [interesting netcat commands](https://phoenixnap.com/kb/nc-command)
- `telnet <host> <port>`
## Stegonography
- StegHide
- [FotoForensics](https://fotoforensics.com/)
- binwalk then carve with `dd if=<inputfile> of=<outputfile> bs=1 skip=<offset>`
