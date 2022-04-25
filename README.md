# IFstatement_within_a_function.py
call a function name and age

def school_age_cal(age,name):
    if age < 19:
        print("enjoy highschool life!", name, "u are only", age)
    elif age == 19:
        print("enjoy college,", name)
    else:
        print("get your first job!")
        
school_age_cal(27, "Iren")#the age and name thats expected in the def func above...
        
