# shopping-list

item = input("what item are you looking for ")
thislist = ["apple", "banana", "cherry", "toilet paper", "sausage", "nerds", "coke"]
if item in thislist:
  print("Yes," +item+ " is in the item list")
else:
    print("no," +item+  " is not in the item list")   
add = input("would you like to add it to cart ")
cart = ["toilet paper", "sausage", "nerds"] 
if (add =="yes"):
    cart.append(item)
    print (cart)
else:
    print (cart)


newitem = input("would you like to check for a new item ")
if (newitem == "yes"):
  newitem = input("what item are you looking for ")
else:
  print("have a good day")
  exit()
if newitem in thislist:
  print("yes, " +newitem+ " is in the item list")
else:
  print ("no, " +newitem+ " is not in the item list")     
add = input("would you like to add it to the cart ")
if (add =="yes"):
  cart.append(newitem)
  print (cart)
else:
  print (cart)
