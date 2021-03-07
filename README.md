# ezdivide
# Divide calculator , Python
# Just a simple divide script written in Python
def dividend(Divisor):
    dividend = int(input("Dividend > "))
    divided_value = dividend/Divisor
    return divided_value

Divisor = int(input("Divisor > "))
divided = dividend(Divisor)

print("You have : ")
print(dividend)
print("If you have : ")
print(Divisor)
