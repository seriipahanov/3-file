num = int(input("Введите число: "))
is_prime = True
for i in range(2, num):
    if num % i == 0:
        is_prime = False
        break
if is_prime:
    print("Число является простым")
else:
    print("Число не является простым")
