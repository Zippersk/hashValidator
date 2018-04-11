## *HashValidator for Fitcrack* ##
Simple hash validator from Hashcat.


## *Usage* ##
```
./hashValidator -m <hash_type> [ <hash> <hash_file> ]
```

## *Examples* ##

```
./hashValidator -m 0 47bce5c74f589f4867dbd57e9ca9f808
47bce5c74f589f4867dbd57e9ca9f808 OK   


./hashValidator -m 0 TEST
0cc175b9c0f1b6a831c399e269772661 OK
aaa Line-length exception
bbb Line-length exception
0cc175b9c0f1b6a831c399e269772661 OK
0cc175b9c0f1b6a831c399e269772661 OK

```