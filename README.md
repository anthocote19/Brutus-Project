Create a project named Brutus.

Add the MD5 library.

An MD5 is an unsigned char array of 16 packets.

unsigned char check[17] = {0};

To get the MD5 in order to crack it, use scanf in hexadecimal mode with a space between the packets.

scanf("%x %x %x ... ", &check[0], &check[1], ...);

Ask the user to get the assumed password size.

int pSize;

To define the characters to be tested, use an alphabet.

char *alphabet = "abcdefghijklmnopqrstuvwxyz";

Create an array of 255 characters to define a password to test.

Create a digest array of unsigned char to put the generated MD5 of the password from the previous array.

Create a loop to test all the options.

md5((unsigned char *) toCheck, pSize, digest);

Crack 6057f13c496ecf7fd777ceb9e79ae285.

Crack de9c3cbac5e22a64b3746708837ddd16.
