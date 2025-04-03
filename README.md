x = input("Nhập dãy số: ")
a = x.split()
def tong_chan(b):
    s = 0
    for i in range(len(b)):
        if int(b[i]) % 2 == 0:  
            s = s+int(b[i])
    print("Tổng các số chẵn:", s)
    return
tong_chan(a)
