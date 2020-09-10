# XOR File Encryption #

> COMPSCI 210  
> University of Auckland  
> Simon Shan

Encrypts files with a password byte-by-byte using a XOR cipher.

Decryption is the same process,  
only the password *used to encrypt* will decrypt the file.

### compile ###

```bash
$ gcc fileEncrypt.c -o xor
```

### usage ###

```
$ ./xor <filename> <password>
```

### example ###
```bash
$ ./xor auckland.jpg password1
```
will produce `new-auckland.jpg` file, to decrypt:
```bash
$ ./xor new-auckland.jpg password1
```
`new-new-auckland.jpg` will be identical to the original

## Authors ##

- **simon** - *~~buy my merch~~ hire me pls* - [mightbesimon](https://github.com/mightbesimon)

## License ##

MIT

## Acknowledgments ##

- **these are just my sample codes, if you misuse them its not my problem**
- this was fun assignment, easy to code and useful!