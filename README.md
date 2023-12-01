# shifting-operation
#To circulate the values
list1 = [1,2,3,4,5]
list2 = [6,7,8,9,0]
newlist1 = list1[1:]+list1[:1]
print("after circulation(left shift):",newlist1)
newlist2 = list2[-1:]+list2[0:-1]
print("after circulation(right shift):",newlist2)
