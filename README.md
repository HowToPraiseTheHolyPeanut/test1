#GCD/NWD


num1 = int(input("Wpisz pierwsza liczbe: \n"))
num2 = int(input("Wpisz druga liczbe: \n"))

if num2>num1:
    mn = num1

else:
    mn = num2

for i in range(1, mn+1):
    if num1%i==0 and num2%i==0:
        nwd = i

print(f"NWD tych dwuch liczb wynosi {nwd}")
