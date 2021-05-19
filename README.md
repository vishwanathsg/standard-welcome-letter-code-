# standard-welcome-letter-code-
This code takes important inputs, and then types the welcome letter with the respective input

total_students=int(input("Enter the number of students: "))
#Taking user input for number of students
print()

listn = []
for x in range(total_students):
    print()
    names = input("Enter candidate's name: ")
    #User input on candidate's name
    listn.append(names)

listad = []
for y in range(total_students):
    print()
    admission_id = input("Enter the Admission ID: ")
    #User input on admission ID
    listad.append(admission_id)

listcap = []
for z in range(total_students):
    print()
    cap_rank = input("Enter the CAP rank: ")
    #User input on CAP Rank
    listcap.append(cap_rank)

for x in range(total_students):
    print()
    print("Hi",listn[x],"\n\n Congratulations...!", listn[x], "\nYou got selected for next round of recruitment process.\n Submit your academic credential including primary and secondary certificates.\n Your admission ID is",listad[x], "and will be eligible for the next round of interview with a CAP rank of",listcap[x],".\n If you submit all the documents on time and process university might offer you a scholarship.")
