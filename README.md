# M013-Group5
ECS 101 Project #1

7 long bits and 4 short bits 

input_file = open("text_input")
file_string = input_file.read()

def findcode(x: str):
    ans = ""
    for i in x:
       if i == "a":
           ans += "11011"
       elif i == "b":
           ans += "0000001"
       elif i == "c":
           ans += "0000011"
       elif i == "d":
            ans += "0000111"
       elif i == "e":
           ans += "10010"
       elif i == "f":
           ans += "0001111"
       elif i == "g":
           ans += "0011111"
       elif i == "h":
           ans += "0111111"
       elif i == "i":
           ans += "11111"
       elif i == "j":
           ans += "0000010"
       elif i == "k":
           ans += "0000100"
       elif i == "l":
           ans += "0001000"
       elif i == "m":
           ans += "0010000"
       elif i == "n":
           ans += "0100000"
       elif i == "o":
           ans += "10100"
       elif i == "p":
           ans += "0000101"
       elif i == "q":
           ans += "0001010"
       elif i == "r":
           ans += "0010101"
       elif i == "s":
           ans += "0101011"
       elif i == "t":
           ans += "0000110"
       elif i == "u":
           ans += "11001"
       elif i == "v":
           ans += "0001100"
       elif i == "w":
           ans += "0011000"
       elif i == "y":
           ans += "10000"
       elif i == "z":
           ans += "0110000"
       elif i == "x":
           ans += "0000111"
       elif i == "A":
           ans += "11101"
       elif i == "B":
           ans += "0001110"
       elif i == "C":
           ans += "0011100"
       elif i == "D":
           ans += "0111000"
       elif i == "E":
           ans += "11000"
       elif i == "F":
           ans += "0001101"
       elif i == "G":
           ans += "0011011"
       elif i == "H":
           ans += "0110111"
       elif i == "I":
           ans += "11010"
       elif i == "J":
           ans += "0001001"
       elif i == "K":
           ans += "0010010"
       elif i == "L":
           ans += "0100100"
       elif i == "M":
           ans += "0011101"
       elif i == "N":
           ans += "0111101"
       elif i == "O":
           ans += "10011"
       elif i == "P":
           ans += "0110101"
       elif i == "Q":
           ans += "0111010"
       elif i == "R":
           ans += "0101100"
       elif i == "S":
           ans += "0001011"
       elif i == "T":
           ans += "0111110"
       elif i == "U":
           ans += "11110"
       elif i == "V":
           ans += "0100111"
       elif i == "W":
           ans += "0100010"
       elif i == "Y":
           ans += "10001"
       elif i == "Z":
           ans += "0101000"
       elif i == "X":
           ans += "0010100"
       elif i == "\n":
           ans += "0110100"
       elif i == " ":
           ans += "10110"
       elif i == "and":
           ans += "10101"
       elif i == "the":
           ans += "11100"
       elif i == ".":
           ans += "10111"
       elif i == ",":
           ans += "0110011"
       elif i == "!":
           ans += "0111001"
       elif i == "'":
           ans += "0010011"
       elif i == '"':
           ans += "0100101"
    y = ans.count("1") + ans.count("0")
    y = str(y)
    ans = y + "." + ans
    print(ans)

findcode(file_string)
