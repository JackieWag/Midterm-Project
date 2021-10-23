### Python Projects

**Started-** This was my first time ever learning to code. This was how to find a volume or a cylinder.
```
from math import pi  

def get_positive_value_from_user(prompt):  
    while True:  
        try:  
            value = float(input(prompt)). 
            if value < 0:  
                print("The value entered must be 0 or greater."). 
                continue  
            break  
        except Exception as e:  
            print(e)  
    return value  

def calculate_circular_cone_volume(radius, height):  
    volume = pi * radius**2 * height / 3  
    return volume  

def generate_report(radius, height, volume):  
    print("A right circular cone of radius =", radius, "and height =", height, "has a volume of", volume)  

def main():  
    radius = get_positive_value_from_user("What is the radius?")  
    height = get_positive_value_from_user("What is the height?")  
    volume = calculate_circular_cone_volume(radius, height)  
    generate_report(radius, height, volume)  


main()
```
