# Python-assignment--02
input_1=int(input())       #Input:97
input_2=int(input())       #Input:123

ascii_dict = {}

for char in range(input_1,input_2):        #Expected output:{'a':97,'b':98,.....,'z':122}
    ascii_dict[chr(char)] = char
print(ascii_dict)                          #My output:{'a':97,'b':98,.....,'z':122}
