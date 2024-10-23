- 👋 Hi, I’m @joudalhallaq
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
joudalhallaq/joudalhallaq is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
"""print("welcome!")
information = [[20221,"omar",[12,15]],
              [20202,"ahmad",[13,14]],
              [20203,"qaia",[18,17]]]
for s in information :
  print (type(s[0]))
  print (f"{s[0]}@uop.edu.jo")
  print(s[2][0]+s[2][1])
  print (sum(s[2]))
courses= ("DS programing 1","Data Straucture ","Database")

print (type (courses))
for n in courses :
  print (n)

print (courses) 
courses_iter =iter(courses)
while true :
  try:
    print (next(courses_iter))
  except:
    break """

"""********************************************************

for i in range (1,11):
  print (i)

print ([*range (1,11)])
for i in  range (0,11,2):
  print (i)
for i in  range (10,0,-1):
  print (i)
  ********************************************************"""


student=['sarah manasrah','jood hallaq','osama jarrar','mais abuhallawah ']
for s in student :
  student_fname =[s.split(" ")[0].lower() for s in student]
  student_emails=[s+"{s}@uopstd.edu.jo"for s in student_fname]
  student_emails=[f"{s}@uopstd.edu.jo"for s in student_fname]
  print ( student_fname )
  print ( student_emails )
  grades =[50,49,90,85]
  grades_succ=len([m for m in grades if m>=50])/len(grades)
  print (grades_succ)
