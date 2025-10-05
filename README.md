Encview v6.0
==============
This is my own personal password manager.

If you stumble across this program, use it at your own risk!

No documentation, no license (public domain), no guarantee.

It works like a very basic text editor, except that all files are encrypted using a proprietary encryption algorithm.
Yes, I know you are not supposed to design your own encryption algorithm, but by doing this, I can guarantee that
there are no hidden backdoors that will allow unwanted decryption.

Written using the Free Pascal compiler.

This uses my own encryption algorithm. I am happy to give an explanation of the algorithm on request, or you can
examine the source code.

The latest version does zcompression on the encrypted files to make them smaller. 
If you are already using this program, you MUST decrypt your file using the previous version into a plain text file,
then re-encrypt using the latest version. The latest version is not compatible with files created by earlier versions.
