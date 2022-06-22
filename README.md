# Tip calculator Using Python

bill=float(input("please privede amound of bill"))
people=int(input("how many people:"))
tip=int(input("Tip would you like to give(10%,12%,14%)"))

bill_with_tip= (bill*tip/100)+bill
final_bill= round(bill_with_tip/people,2)
final_bill="{:.2f}".format(final_bill)
print(final_bill)
