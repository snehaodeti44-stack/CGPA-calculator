def grade_point(grade):
    grades = {
        'O': 10,
        'A+': 9,
        'A': 8,
        'B+': 7,
        'B': 6,
        'C': 5
    }
    return grades.get(grade.upper(), 0)

n = int(input("Enter number of subjects: "))

total_points = 0
total_credits = 0

for i in range(n):
    credit = int(input(f"Enter credits for Subject {i+1}: "))
    grade = input(f"Enter grade for Subject {i+1}: ")

    total_points += credit * grade_point(grade)
    total_credits += credit

cgpa = total_points / total_credits

print("\nCGPA =", round(cgpa, 2))
