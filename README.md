# TOTP
Modification of TOTP code by ietf to produce RFC 6238 TOTP of max 10 characters. IETF's version produces maximum of 8 characters TOTP
(Taken from https://tools.ietf.org/html/rfc6238)

#Instructions
1. Compile file
2. Run file with the arguments
  a. Character length of TOTP to be generated (<=10 Characters)
  b. Token Shared secret in Hexadecimals

#Example run (Windows CMD):
>javac TOTP.java

>java TOTP 10 726F796B69617440686F746D61696C2E636F6D4844454348414C4C454E4745303033

* P.S default is HMAC 512, you can edit the code yourself to use other hash methods.
