# restaurant-manegment-program-in-python
menu= {
    'pizza':40,
    'passta':50,
    'burger':60,
    'salad':70,
    'hotdog':80,
    'coffee':90,
}
print("welcome to our python restaurant")
print("pizza:  RS 40\npassta: RS 50\nburger: RS 60\nsalad:  RS 70\nhotdog: RS 80\ncoffee: RS 90")
order_total=0
item_1=input("enter the name of item you want to order:")
if item_1 in menu:
    order_total += menu[item_1]
    print(f"your item {item_1} has been added to your order\n")
else:
  print(f"sorry this {item_1} item is not mention our menu\n")

next=input("do you want to add another item (yes/no):")
if next =="yes":
  item_2=input("enter the name of second item:")
  if item_2 in menu:
    order_total += menu[item_2]
    print(f"your item {item_2} has been added to your account\n")
  else:
    print(f"sorry this {item_2} item is no mention our menu\n")

print(f"your total amount of items is :{order_total}\n")

print("********enjoy your time with python resturant*****\n")
