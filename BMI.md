mass=int(input("Enter your weight in kg:"))
height=float(input("Enter your hieght in meter :"))
BMI=mass / height**2
def round(BMI):
    print(BMI)
print(BMI)    
if BMI <= 20 :
    print("ohhh!You are underweight")
if BMI >= 20 and BMI <= 30:
    print("Great! You are healthy")    
else:
    print(" ops !You are unhealthy")
