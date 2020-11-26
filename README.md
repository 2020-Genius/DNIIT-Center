# DNIIT-Center

n = int(input("Enter the number = "))
x = n
sum = 0
while n >0:
	d = n%10
	sum = sum+d*d*d
	n = n//10
print(sum)
if sum ==x:
	print("Number is Armstrong number")
else:
	print("Not armstrong number")
