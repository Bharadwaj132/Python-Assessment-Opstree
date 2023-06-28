#Ques 1: Write a program that takes a list of numbers from the user and prints the third largest and third smallest numbers from the list.
list_num = [4, 5, 1, 3, 6 , 10, 9, 1, 5]
list_num = list(set(list_num))
list_num.sort()
print (list_num)

print(f'Third small number in the list is {list_num[2]}')
print(f'Third largest number in the list is {list_num[-3]}')


'''Ques 2: Write a program that takes a string from the user and prints the number of times two vowels and two consonants occur together in the string.
Example - aahjuhiogy
Answer - Consonants - 2
Vowels - 2'''

string = 'aahjuhiogy'
vowels = 'aeiou'
vowel_count = 0
consonants_count = 0

for i in range(1, len(string)):
    if string[i] in vowels and string[i-1] in vowels:
        vowel_count += 1
    if string[i] not in vowels and string[i-1] not in vowels:
        consonants_count += 1

print(f'Vowels - {vowel_count}')
print(f'Consonants - {consonants_count}')


#Ques 3: Write a program that takes a positive integer from the user and prints the sum of its digits through recursion

def sumofdigit(n):
    n = str(n)
    if len(n) == 1:
        return int(n)
    return int(n[0]) + sumofdigit(n[1:])

print(sumofdigit(291))
