# OpenSPX
Make post-quantum file signatures.

# Usage
spx [OPTION]... [FILE]...

**Options**

***-s, --sign*** Make file signatures only

***-v, --verify*** Verify file signatures only

***--export-seed*** Outputs the secret seed value

***--import-seed*** Sets the value from input

***-p, --public-import*** [*KEY*] Verify files by a public key
 
***-e, --public-export*** Outputs the public key

# Requirements
`python3.7 cryptography keyring pyspx`

**Supported OS**

Guaranteed to work on GNU/Linux like Debian 10, Ubuntu 20.04 or higher
