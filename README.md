# Lesson-7-lists

"Das - 7"
    "N-1"
        list1 = ["M", "na", "i", "Ke"]
        list2 = ["y", "me", "s", "lly"]
        print(list1[0] + list2[0], list1[1] + list2[1], list1[2] + list2[2], list1[3] + list2[3])


    "N-2"
        listik = []
        n = int(input("Enter number of elements : "))
        for i in range(0, n):
            element = int(input())
            element = element ** 2
            listik.append(element)

        print(listik)


    "N-3"
        i = []
        count = 0
        listok = [1, 2, 3, 4, 5, 6]
        for i in listok:
            count += i
        print(count)



    "N-4"
        v = []
        count1 = 0
        listok1 = [1, 2, 2, 4, 5, 3, 3, 3, 4, 5, 6]
        for v in listok1:

            if listok1.count(v) > 1:
                listok1.remove(v)

        print(listok1)


    "N-5"
        d = []
        f = []
        listok2 = [1, 2, 2, 4, 5, 3, 3, 3, 4, 5, 6]
        for f in listok2:
            listok2.count(f)
            if listok2.count(f) == 1:
                d.append(f)


        print(d)

