# AI-Project

import random

#This code is not from any source
#Binary is a mathematical numeral system that is expressed in the base 2's complement notation.
#This function generates a random numner with a given length
def generate_binary_string(n):
    n = int(n)
    binary_string = ''
    for i in range(n):
#This line converts a random number between 0 and 1 to a binary string
        binary_string += random.choice('01') 

    return binary_string

#The n = numbers that are by 10s
# This function generates a binary string of random length n and returns it as a string
if __name__ == '__main__':
    print(generate_binary_string(1))
    print(generate_binary_string(10))
    print(generate_binary_string(20))
    print(generate_binary_string(30))
    print(generate_binary_string(40))
    print(generate_binary_string(50))
    print(generate_binary_string(60))
    print(generate_binary_string(70))
    print(generate_binary_string(80))
    print(generate_binary_string(90))
    print(generate_binary_string(100))
    print(generate_binary_string(110))
    print(generate_binary_string(120))
    print(generate_binary_string(130))
    
    
    
    
# THE HMAC & Secret Key Algorithms  
#The code below did not come from any source.
import hmac
import hashlib

# Hash Algorithms mathematical functions that takes data and makes it unreadable.
# HMAC: message authentication code using HMAC algorithm.
# Crypto: message authentication code using secret key algorithm.

# SHA is more secure than the other algorithms in hash.
# SHA-1 is a version of hash secure algorithm used in cryptographic applications.
# SHA -1 creates 160-bit outputs
#This is a sample code to generate a HMAC signature.
hmac_key = input("Enter the HMAC key: ")
message = input("Enter the message: ")
signature = hmac.new(hmac_key.encode(), message.encode(), hashlib.sha1).hexdigest()
print(signature)

if hmac_key == signature:
    print("HMAC signature is valid")

else:
    print("HMAC signature is invalid")

import hmac
import hashlib

# SHA - 256 is a version of hash secure algorithm used in cryptographic applications.
# This algorithm takes an input of data and provides it in a 256-bit hash output.
#This is a sample code to generate a HMAC signature.
hmac_key = input("Enter the HMAC key: ")
message = input("Enter the message: ")
signature = hmac.new(hmac_key.encode(), message.encode(), hashlib.sha256).hexdigest()
print(signature)

if hmac_key == signature:
    print("HMAC signature is valid")

else:
    print("HMAC signature is invalid")

import hmac
import hashlib

# SHA - 512 is a version of hash secure algorithm used in cryptographic applications.
# Using this algorithm, you can hash a message input of any size. The message will be processed in 1024 bits of data.
#This is a sample code to generate a HMAC signature.
hmac_key = input("Enter the HMAC key: ")
message = input("Enter the message: ")
signature = hmac.new(hmac_key.encode(), message.encode(), hashlib.sha512).hexdigest()
print(signature)

if hmac_key == signature:
    print("HMAC signature is valid")

else:
    print("HMAC signature is invalid")

import string
import secrets

# Line 58 imports the secrets module.
# Secret key is a crytographic that generates random numbers for managing passwords, authentication, etc.
# Generate
# URL-safe is used to generate random URL-safe strings containing nbytes of characters.
#This function generates a secret key.
secret_key = secrets.token_urlsafe(32)
print(secret_key)
secret_key = input("Enter the secret key: ")
print(secret_key)

if secret_key == secret_key:
    print("Secret key is valid")

else:
    print("Secret key is invalid")

import string
import secrets

# import secrets module
# the code below generates a token with a length of 128 bits.
#the next line will generate a random string.
#Generate
#This function generates a secret key.
secret_key = secrets.token_hex(128)
print(secret_key)
secret_key = input("Enter the secret key: ")
print(secret_key)

if secret_key == secret_key:
    print("Secret key is valid")

else:
    print("Secret key is invalid")

import string
import secrets

#import secrets module
# the code below generates a token with a byte size of 256.
#the next line will generate a random string.
#Generate
#This function generates a secret key.
secret_key = secrets.token_bytes(256)
print(secret_key)
secret_key = input("Enter the secret key: ")
print(secret_key)

if secret_key == secret_key:
    print("Secret key is valid")

else:
    print("Secret key is invalid")


import string
import secrets
#import secrets module
# the code below generates a token with a byte size of 16.
#Generate
#This function generates a secret key.
secret_key = secrets.token_bytes(16)
print(secret_key)
secret_key = input("Enter the secret key: ")
print(secret_key)

if secret_key == secret_key:
    print("Secret key is valid")

else:
    print("Secret key is invalid")

