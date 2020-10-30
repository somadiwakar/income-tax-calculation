#income tax calculation as per 2020 tax information
income=int(input("Enter your income: "))
tax = 0 
cess = 0 
if income<=250000:
    tax=0
elif income<=500000:
    tax=(income-250000)*0.05
elif income<=750000:
    tax=12500+(income-500000)*0.10
elif income<=1000000:
    tax=12500+75000+(income-750000)*0.15
elif income<=1250000:
    tax=12500+75000+200000+(income-1000000)*0.20
elif income<=1500000:
    tax=12500+75000+200000+312500+(income-1250000)*0.25
else:
    tax=12500+75000+200000+312500+450000+(income-1500000)*0.30
cess=tax*0.04
Total_tax=tax+cess
print("Income Tax=",tax)
print("Health and Education cess=",cess)
print("Total=",Total_tax)
