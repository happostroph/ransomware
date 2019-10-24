# Ransomware

## What is a ransomware?

Ransomware is a type of malware that encrypt files of users. To decrypt them generally the user is force to pay a ransom.

## Summary

This project is developp after a need during a POC of a ransomware which can duplicate himself with the ip address of the different target.

## Objectives

### Cryptor

#### Crypted

- [ ] List files
- [ ] Encrypt files with AES-256-CTR.
- [ ] Generate an id for each crypted system.
- [ ] Delete shadow copy

#### Message

- [ ] Generate message in html.

#### Lateral Movement

- [ ] Communication with the server to have the informations on the next target
- [ ] Connect to the next target (Pass the hash ?)
- [ ] Copy the ransomware on the next target
- [ ] Execution on the next target

### Decryptor

- [ ] Communication with the server to verify decrypt key
- [ ] Decrypt files

### Web server

- [ ] Store id : decrypt key
- [ ] Send information on host to replicate (ip, hash)

## Disclaimer

Use this tool at your own risk. I'm not responsible or liable if you damage your own system or others. Follow all local, state, federal, and international laws as it pertains to your geographic location. Do NOT use this tool maliciously as it is being released for educational purposes. This tools intended use is in cyber exercises or demonstrations of adversarial tools.
