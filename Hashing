def hashofseatnum(n):
   
    hashvalue=(int(n[-3:])-1)
    return (hashvalue)



studentrecord=["B00000000"]*8
n=len(studentrecord)

# for entering seat no. in an enpty list:
for i in range (n+1):
    
    seatno=input("enter students seat no:")
    hv=hashofseatnum(seatno)
    print(studentrecord)
    
    studentrecord[hv]=seatno

print(studentrecord[hv])
# for searching a seat no. from the list:

seatno=input("enter seat no. to searc:")
hv=hashofseatnum(seatno)
if(studentrecord[hv]==seatno):
    print("seat no is recorded at INDEX no",hv)
else:
    print("seat no not available in the list")
    
