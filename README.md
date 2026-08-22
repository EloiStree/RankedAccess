# Ranked Access

> **Public key registration for ranked players in my games.**

You can claim a positive integer by supporting me on Buy Me a Coffee:
https://buymeacoffee.com/apintio

The idea is simple: **all my games remain fully playable without a RankedAccess key.**     
However, to participate in a tournament, I need to verify that your code is actually playing for you.   


**Positive integers** represent **users who have claimed and purchased a key**.
* A positive integer can only be changed through a **cryptographically signed request** from the key owner.
* This ensures that the registered identity cannot be changed by someone else.

**Negative integers** represent **guest keys**.
* Guest keys can be overridden by the repository administrator.
* They are intended for **temporary guest players**, such as players participating in tournaments without a permanent RankedAccess key.
* The repository administrator can change or reassign these keys when needed.

**0 Integer is the admin keys.**
If you do yourself a tournament with my applications/games.     
The 0 key is for the admins.    

---

> I assume that if you are reading this, you already know what an RSA or ECC key is, since you have played my tutorials and/or games.

Choose a **positive integer** that you like, as long as it has not already been claimed.

Then generate two RSA public key using this format:
[pbit4096_b58_pkcs1_sha256](https://github.com/EloiStree?tab=repositories&q=)

Send me the two generated public key:
- Playing Key is to be used.
- Owner key is to be able to change the Playing Key
   

> **DO NOT LOSE YOUR OWNER PRIVATE KEY.**   
> **PLAY GAME WITH THE PLAYING KEY TO AVOID BE HACK AND LOSE THE OWNER KEY**   
> To prevent someone else from impersonating you, **we only trust the owner of the corresponding owner private key.**   





