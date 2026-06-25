"A simple good total semester scores calculator for students of Presidential, specializated, Al-khavarezmi schools and other for other students whose scools calculate score by multiplying averages by 0.4 and 0.6." 

print ("hello, my boy! Tell me your assesments and end of semester exams' scores and i'm gonna calculate it instead of you")
a =int(input("Enter the number of assesments you have assigned: "))
if a == 2:
    assesment1 = int(input("Enter your first assesment score: "))
    assesment2 = int(input("Enter your second assesment score: "))
    total = (assesment1 + assesment2) / 2
    print(f"Your average score is: {total}")
elif a == 3:
    assesment1 = int(input("Enter your first assesment score: "))
    assesment2 = int(input("Enter your second assesment score: "))
    assesment3 = int(input("Enter your third assesment score: "))
    total = (assesment1 + assesment2 + assesment3) / 3
    print(f"Your average score is: {total}")
elif a == 4:
    assesment1 = int(input("Enter your first assesment score: "))
    assesment2 = int(input("Enter your second assesment score: "))
    assesment3 = int(input("Enter your third assesment score: "))
    assesment4 = int(input("Enter your fourth assesment score: "))
    total = (assesment1 + assesment2 + assesment3 + assesment4) / 4
    print(f"Your average score is: {total}")
elif a == 5:
    assesment1 = int(input("Enter your first assesment score: "))
    assesment2 = int(input("Enter your second assesment score: "))
    assesment3 = int(input("Enter your third assesment score: "))
    assesment4 = int(input("Enter your fourth assesment score: "))
    assesment5 = int(input("Enter your fifth assesment score: "))
    total = (assesment1 + assesment2 + assesment3 + assesment4 + assesment5) / 5
    print(f"Your average score is: {total}")
b = int(input("Enter your end of semester exam score: "))
final_score = (total * 0.6) + (b * 0.4)
print(f"Your final score is: {final_score}")
