# HOTEL-MENU
#This code describes to order item by sitting at one place
print("HOTEL TAJ")
print("MENU:")
print("CHINESE:")
print(1,".Chicken chatpat-60$")
print(2,".Chicken Pakodi-70$")
print(3,".Chicken manchuria-80$")
print(4,".Chicken khebab-90$")
print("BIRYANI:")
print(5,".Chicken Biryani-100$")
print(6,".Chicken fried biryani-100$")
print(7,".Chicken spl-130$")
print(8,".Chicken family pack-200$")
print("SHAKES")
print(9,".Oreo Milk shake-15$")
print(10,".Kitkat Milk shake-15$")
print(11,"Strawberry Milk shake-20$")
print(12,"Vanilla Milk shake-15$")
print(13,"Chocolate Milk shake-15$")
x=int(input("Enter a choice u need to order"))
y=int(input("Enter how many would u like to order"))
for i in range (0,x):
    z="HOTEL TAJ"
    print(z.center(15))
    d="BILL"
    print(d.center(15))
    import datetime
    e = datetime.datetime.now()
    print (e.strftime("%a, %d %b %Y"))
    print (e.strftime("%d/%m/%Y"))
    print (e.strftime("%I:%M:%S %p"))
    f="ITEM:"
    print(f.center(15))
    if x==1:
        print("Chicken Chatpat-60$")
        print("Total price=",(60*y),"$")
        break
    elif x==2:
        print("Chicken pakodi-70$")
        print("Total price =",(70*y),"$")
        break
    elif x==3:
        print("Chicken manchuria-80$")
        print("Total price=",(80*y),"$")
        break
    elif x==4:
        print("Chicken khebab-90$")
        print("Total price=",(90*y),"$")
        break
    elif x==5:
        print("Chicken Biryani-100$")
        print("Total price=",(100*y),"$")
        break
    elif x==6:
        print("Chicken fried biryani-100$")
        print("Total price=",(100*y),"$")
        break
    elif x==7:
        print("Chicken spl-130$")
        print("Total price=",(130*y),"$")
        break
    elif x==8:
        print("Chicken family pack-200$")
        print("Total price",(200*y),"$")
        break
    elif x==9:
        print("Oreo Milk shake-15$")
        print("Total price",(15*y),"$")
        break
    elif x==10:
        print("Kitkat Milk shake-15$")
        print("Total price",(15*y),"$")
        break
    elif x==11:
        print("Strawberry Milk shake-20$")
        print("Total price",(20*y),"$")
        break
    elif x==12:
        print("Vanilla Milk shake-15$")
        print("Total price",(15*y),"$")
        break
    elif x==13:
        print("Chocolate Milk shake-15$")
        print("Total price",(15*y),"$")
        break
print("THANK YOU,VISIT AGAIN !!")     

    
