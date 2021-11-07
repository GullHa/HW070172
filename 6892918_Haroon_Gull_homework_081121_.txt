Python 3.10.0 (tags/v3.10.0:b494f59, Oct  4 2021, 19:00:18) [MSC v.1929 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
# Chapter02Exercise01.py
def main():
    print("The program converts Celsius temperatures to Fahrenheit.")
    print()
    celsius = eval(input("What is the Celsius temperature? "))
    fahrenheit = 9/ 5 * celsius + 32
    print("The temperature is", fahrenheit, "degrees Fahrenheit.")

main()
The program converts Celsius temperatures to Fahrenheit.

What is the Celsius temperature? 21
The temperature is 69.80000000000001 degrees Fahrenheit.

# Chapter02Exercise02.py
def main():
    celsius = eval(input("What is the Celsius temperature? "))
    fahrenheit = 9/ 5 * celsius + 32
    print("The temperature is", fahrenheit, "degrees Fahrenheit.")
    input("Press the <Enter> key to quit.")

    
main()
What is the Celsius temperature? 21
The temperature is 69.80000000000001 degrees Fahrenheit.
Press the <Enter> key to quit.
