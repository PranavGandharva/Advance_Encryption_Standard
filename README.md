# Advance_Encryption_Standard
# Objective: 
Implementation of the contemporary industrial standard on encryption AES.
# Steps
(for testing your program of original AES and for result format)
==========================================================
ID1 = 103 555 abc (Alice Smith)

ID2 = 103 555 xyz (Bob Jones)

Group Code: (A, B) = (x, y)

Assigned Plaintext and Key:

0011 2233 4455 6677 8899 aabb ccdd eeff

0001 0203 0405 0607 0809 0a0b 0c0d 0e0f

The program is written in Python for operating system Fedora

Original AES with Group Code (x, y)

----------------------------------------------------------

Plaintext:

00 11 22 33 44 55 66 77 88 99 aa bb cc dd ee ff

Key:

00 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d 0e 0f

Round Keys:

----------------------------------------------------------

Encrypted round keys:

----------------------------------------------------------

round 0 key:

00 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d 0e 0f

round 1 key:

d6 aa 74 fd d2 af 72 fa da a6 78 f1 d6 ab 76 fe

round 2 key:

b6 92 cf 0b 64 3d bd f1 be 9b c5 00 68 30 b3 fe

round 3 key:

b6 ff 74 4e d2 c2 c9 bf 6c 59 0c bf 04 69 bf 41

round 4 key:

47 f7 f7 bc 95 35 3e 03 f9 6c 32 bc fd 05 8d fd

round 5 key:

3c aa a3 e8 a9 9f 9d eb 50 f3 af 57 ad f6 22 aa

round 6 key:

5e 39 0f 7d f7 a6 92 96 a7 55 3d c1 0a a3 1f 6b

round 7 key:

14 f9 70 1a e3 5f e2 8c 44 0a df 4d 4e a9 c0 26

round 8 key:

47 43 87 35 a4 1c 65 b9 e0 16 ba f4 ae bf 7a d2

round 9 key:

54 99 32 d1 f0 85 57 68 10 93 ed 9c be 2c 97 4e

round 10 key:

13 11 1d 7f e3 94 4a 17 f3 07 a7 8b 4d 2b 30 c5

----------------------------------------------------------

Encrypted data rounds:

----------------------------------------------------------

Input:

00 11 22 33 44 55 66 77 88 99 aa bb cc dd ee ff

Round 0:

00 10 20 30 40 50 60 70 80 90 a0 b0 c0 d0 e0 f0

Round 1 :

89 d8 10 e8 85 5a ce 68 2d 18 43 d8 cb 12 8f e4

Round 2 :

49 15 59 8f 55 e5 d7 a0 da ca 94 fa 1f 0a 63 f7

Round 3 :

fa 63 6a 28 25 b3 39 c9 40 66 8a 31 57 24 4d 17

Round 4 :

24 72 40 23 69 66 b3 fa 6e d2 75 32 88 42 5b 6c

Round 5 :

c8 16 77 bc 9b 7a c9 3b 25 02 79 92 b0 26 19 96

Round 6 :

c6 2f e1 09 f7 5e ed c3 cc 79 39 5d 84 f9 cf 5d

Round 7 :

d1 87 6c 0f 79 c4 30 0a b4 55 94 ad d6 6f f4 1f

Round 8 :

fd e3 ba d2 05 e5 d0 d7 35 47 96 4e f1 fe 37 f1

Round 9 :

bd 6e 7c 3d f2 b5 77 9e 0b 61 21 6e 8b 10 b6 89

Round 10:

69 c4 e0 d8 6a 7b 04 30 d8 cd b7 80 70 b4 c5 5a

----------------------------------------------------------

Final Output:

69 c4 e0 d8 6a 7b 04 30 d8 cd b7 80 70 b4 c5 5a

----------------------------------------------------------
