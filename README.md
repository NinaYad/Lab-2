
print("Введите цифру действия которое хотите произвести "
      "\n 1.Транспонирование \n 2.Умножение \n 3.Определение ранга")
s = int(input())
if s>3:
    print ("Ошибка")
if s == 1:
    print("Введите число строк")
    n = int(input())
    print("Введите число столбцов")
    m = int(input())

    if n == 1 and m == 2:
        print("Введите матрицу которую хотите транспонировать")
        m1 = [int(input()), int(input())]
        print (m1[0])
        print (m1[1])
    if n == 2 and m == 1:
        print("Введите матрицу которую хотите транспонировать")
        m1 = [int(input()), int(input())]
        print (m1[0],m1[1])
    if n == 1 and m == 3:
        print("Введите матрицу которую хотите транспонировать")
        m1 = [int(input()), int(input()), int(input())]
        print (m1[0])
        print(m1[1])
        print(m1[2])
    if n == 3 and m == 1:
        print("Введите матрицу которую хотите транспонировать")
        m1 = [int(input()), int(input()), int(input())]
        print (m1[0],m1[1],m1[2])
    if n == 2 and m == 2:
        print("Введите матрицу которую хотите транспонировать")
        m1 = [int(input()), int(input()),int(input()), int(input())]
        print (m1[0],m1[2])
        print(m1[1], m1[3])
    if n == 3 and m == 3:
        print("Введите матрицу которую хотите транспонировать")
        m1 = [int(input()), int(input()),int(input()), \
             int(input()), int(input()),int(input()), int(input()),int(input()), int(input())]
        print (m1[0],m1[3],m1[6])
        print(m1[1], m1[4],m1[7])
        print(m1[2], m1[5], m1[8])
    else:
        print("Ошибка")
res1,res2,res3,res4="","","",""
if s == 2:
    print("Введите число строк матрицы 1")
    n = int(input())
    print("Введите число столбцов матрицы 1")
    m = int(input())
    print("Введите число строк матрицы 2")
    p = int(input())
    print("Введите число столбцов матрицы 2")
    k = int(input())
    if n == 1 and m == 2 and p == 2 and k == 1:
        print("Введите матрицу 1")
        m1 = [int(input()), int(input())]
        print("Введите матрицу 2")
        m2 = [int(input()), int(input())]
        res1 = m1[0]*m2[0]+m1[1]*m2[1]
        print(res1)
    if n == 2 and m == 1 and p == 1 and k == 2:
        print("Введите матрицу 1")
        m1 = [int(input()), int(input())]
        print("Введите матрицу 2")
        m2 = [int(input()), int(input())]
        res1 = m1[0]*m2[0]+m1[1]*m2[1]
        print(res1)
    if n == 1 and m == 3 and p == 3 and k == 1:
        print("Введите матрицу 1")
        m1 = [int(input()), int(input()), int(input())]
        print("Введите матрицу 2")
        m2 = [int(input()), int(input()), int(input())]
        res1 = m1[0]*m2[0]+m1[1]*m2[1]+m1[2]*m2[2]
        print(res1)
    if n == 3 and m == 1 and p == 1 and k == 3:
        print("Введите матрицу 1")
        m1 = [int(input()), int(input()), int(input())]
        print("Введите матрицу 2")
        m2 = [int(input()), int(input()), int(input())]
        res1 = m1[0]*m2[0]+m1[1]*m2[1]+m1[2]*m2[2]
        print(res1)
    if n == 2 and m == 2 and p == 2 and k == 1:
        print("Введите матрицу 1")
        m1 = [int(input()), int(input()), int(input()), int(input())]
        print("Введите матрицу 2")
        m2 = [int(input()), int(input())]
        res1 = m1[0]*m2[0]+m1[1]*m2[1]
        res2 = m1[2]*m2[0]+m1[3]*m2[1]
        print(res1)
        print(res2)
    if n == 1 and m == 2 and p == 2 and k == 2:
        print("Введите матрицу 1")
        m1 = [int(input()), int(input())]
        print("Введите матрицу 2")
        m2 = [int(input()), int(input()), int(input()), int(input())]
        res1 = m1[0]*m2[0]+m1[0]*m2[2]
        res2 = m1[1]*m2[1]+m1[1]*m2[3]
        print(res1)
        print(res2)
    if n == 2 and m == 2 and p == 2 and k == 2:
        print("Введите матрицу 1")
        m1 = [int(input()), int(input()), int(input()), int(input())]
        print("Введите матрицу 2")
        m2 = [int(input()), int(input()), int(input()), int(input())]
        res1 = m1[0]*m2[0]+m1[1]*m2[2]
        res2 = m1[0]*m2[1]+m1[1]*m2[3]
        res3 = m1[2]*m2[0]+m1[3]*m2[2]
        res4 = m1[2]*m2[1]+m1[3]*m2[3]
        print(res1,res2)
        print(res3,res4)
    if n == 3 and m == 3 and p == 3 and k == 1:
        print("Введите матрицу 1")
        m1 = [int(input()), int(input()), int(input()), int(input()), int(input()),\
              int(input()), int(input()), int(input()), int(input())]
        print("Введите матрицу 2")
        m2 = [int(input()), int(input()), int(input())]
        res1 = m1[0]*m2[0]+m1[1]*m2[1]+m1[2]*m2[2]
        res2 = m1[3]*m2[0]+m1[4]*m2[1]+m1[5]*m2[2]
        res3 = m1[6]*m2[0]+m1[7]*m2[1]+m1[8]*m2[2]
        print(res1)
        print(res2)
        print(res3)
    if n == 1 and m == 3 and p == 3 and k == 3:
        print("Введите матрицу 1")
        m1 = [int(input()), int(input()), int(input())]
        print("Введите матрицу 2")
        m2 = [int(input()), int(input()), int(input()), int(input()), int(input()), \
              int(input()), int(input()), int(input()), int(input())]
        res1 = m1[0] * m2[0] + m1[0] * m2[3] + m1[0] * m2[6]
        res2 = m1[1] * m2[1] + m1[1] * m2[4] + m1[1] * m2[7]
        res3 = m1[2] * m2[2] + m1[2] * m2[5] + m1[2] * m2[8]
        print(res1,res2,res3)
    if n == 3 and m == 3 and p == 3 and k == 3:
        print("Введите матрицу 1")
        m1 = [int(input()), int(input()), int(input()), int(input()), int(input()),\
              int(input()), int(input()), int(input()), int(input())]
        print("Введите матрицу 2")
        m2 = [int(input()), int(input()), int(input()), int(input()), int(input()),\
              int(input()), int(input()), int(input()), int(input())]
        res1 = m1[0]*m2[0]+m1[1]*m2[3]+m1[2]*m2[6],m1[0]*m2[1]+m1[1]*m2[4]+m1[2]*m2[7],\
               m1[0]*m2[2]+m1[1]*m2[5]+m1[2]*m2[8]
        res2 = m1[3]*m2[0]+m1[4]*m2[3]+m1[5]*m2[6],m1[3]*m2[1]+m1[4]*m2[4]+m1[5]*m2[7],\
               m1[3]*m2[2]+m1[4]*m2[5]+m1[5]*m2[8]
        res3 = m1[6]*m2[0]+m1[7]*m2[1]+m1[8]*m2[6],m1[6]*m2[1]+m1[7]*m2[4]+m1[8]*m2[7],\
               m1[6]*m2[2]+m1[7]*m2[5]+m1[8]*m2[8]
        print(res1)
        print(res2)
        print(res3)
    else:
        print("Ошибка")
if s == 3:
    print("Введите число строк матрицы ")
    n = int(input())
    print("Введите число столбцов матрицы ")
    m = int(input())
    if n==2 and m==2:
        print("Введите матрицу")
        m1 = [int(input()), int(input()), int(input()), int(input())]
        if m1[0]==0 and m1[1]==0  and m1[2]==0 and m1[3]==0:
            print ("rg = 0")
        elif (m1[0] == 0 and m1[1] == 0) or (m1[2] == 0 and m1[3] == 0):
            print("rg = 1")
        else:
            print("rg = 2")
    if n==3 and m==3:
        print("Введите матрицу")
        m1 = [int(input()), int(input()), int(input()), int(input()),int(input()),\
              int(input()), int(input()), int(input()), int(input())]
        if m1[0]==0 and m1[1]==0  and m1[2]==0 and m1[3]==0 and m1[4]==0\
                and m1[5]==0 and m1[6]==0 and m1[7]==0 and m1[8]==0:
            print ("rg = 0")
        elif (m1[0] == 0 and m1[1] == 0 and m1[2]==0) and (m1[3] == 0 and m1[4] == 0 and m1[5]==0):
            print("rg = 1")
        elif (m1[3] == 0 and m1[4] == 0 and m1[5]==0) and (m1[6] == 0 and m1[7] == 0 and m1[8]==0):
            print("rg = 1")
        elif (m1[0] == 0 and m1[1] == 0 and m1[2]==0) and (m1[6] == 0 and m1[7] == 0 and m1[8]==0):
            print("rg = 1")
        elif (m1[0] == 0 and m1[1] == 0 and m1[2]==0) or (m1[3] == 0 and m1[4] == 0 and m1[5]==0)\
                or (m1[6] == 0 and m1[7] == 0 and m1[8]==0):
            print("rg = 2")
        else:
            print("rg = 3")

