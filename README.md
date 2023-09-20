# lsj

#ts my frist long code about log in

print("#######log in page#########")


username =  input("Enter your user name :")

password  =  input("Enter th password: :")


data_base = {
     "user":"avin" ,
     "pss" : "8819"
 }


if username == data_base["user"]:
     
      if password == data_base["pss"]:
           print("welcome")

      else:
                  
           print("somting wrong")
else:
    
    print("pss is not right ")
     
