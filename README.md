#wap to write number of  even or odd numbers in a list
list_num = [2,3,4,5,6,89,54,67]
list_count= len(list(filter(lambda n: n%2==0,list_num)))
list_count= len(list(filter(lambda n: n%2!=0,list_num)))
print(f"even :",list_count)
print(f"odd :",list_count)
