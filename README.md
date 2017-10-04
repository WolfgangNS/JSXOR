# JSXOR
Javascript-based XOR encryption proof of concept

Proof of concept.
Most browsers will not display non-printable characters (unicode charcodes 1-30), so the purpose of this code is to convert all text to ASCII, XOR the character codes with a repeating salt (put in by the user), and then move the 'unicode reading frame' some arbitrary amount so that all characters are printable.

Useful for sending secret messages.
