# Information

## Overview :

* Interencdec.

## Description :

Can you get the real meaning from this file. Download the file here. 

## Hints :

1. Engaging in various decoding processes is of utmost importance

## Approach :

1. The first thing you have to do is download the file from the link in the terminal and use wget.

```bash
wget https://artifacts.picoctf.net/c_titan/111/enc_flag
```

2. Open the file with the command "cat filename" which produces base64 encryption

```bash
YidkM0JxZGtwQlRYdHFhR3g2YUhsZmF6TnFlVGwzWVROclh6ZzVNR3N5TXpjNWZRPT0nCg==
```
3. Decode with base64

```bash
b'd3BqdkpBTXtqaGx6aHlfazNqeTl3YTNrXzg5MGsyMzc5fQ=='
```

4. After that, delete the quotation marks and the letter b in front

```bash
d3BqdkpBTXtqaGx6aHlfazNqeTl3YTNrXzg5MGsyMzc5fQ==
```
5. Decode back with base64

```bash
wpjvJAM{jhlzhy_k3jy9wa3k_890k2379}
```
6. Finally decode with Caesar cipher
   
## Flag : 

**picoCTF{caesar_d3cr9pt3d_890d2379}**
