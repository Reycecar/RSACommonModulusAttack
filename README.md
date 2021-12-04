# RSACommonModulusAttack
Tool for breaking RSA when you have two messages with a common modulus
All inputs into the python file must be in hex!

For this tool to work, you will need two messages with:
    A ommon modulus value (N)
    The same plaintext value
    Different Exponent values
    Different Ciphertexts

This tool uses a euclidean extended greatest common denominator function found at https://en.wikipedia.org/wiki/Extended_Euclidean_algorithm

