# 4
4
import random

number = random.randint(1, 100)
guess = 0

while guess != number:
    guess = int(input("Đoán một số từ 1 đến 100: "))
    if guess < number:
        print("Cao hơn!")
    elif guess > number:
        print("Thấp hơn!")

print(f"Chúc mừng! Bạn đã đoán đúng số {number}!")
