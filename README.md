str1=input()
str2=""
index=-1
for char in str1:
  str2=str2+str1[index]
  index=index-1
if str1==str2:
      print("PALINDROME")
else:
  print("NOT PALINDROME")
