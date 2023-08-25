# HashCrack

A Python Script used to crack hashes.

```
pip install -r requirements.txt
```

This will install the required tqdm package.

Now to start having your hashes cracked you need to run the python script and add the hash, the text file to crack the hashes from and also mention the hash type.
By default it will crack using **MD5**

```
python HashCrack.py <HASH> <TXT> --hash-type <HASH TYPE>
```

Example

```
python HashCrack.py 6ca13d52ca70c883e0f0bb101e425a89e8624de51db2d2392593af6a84118090 rockyou.txt --hash-type sha256
```
