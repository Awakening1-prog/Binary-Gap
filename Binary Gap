class Solution:
    def binaryGap(self, N: int) -> int:
        a=bin(N)
        a=a[2:]
        l=[]
        for i in range(len(a)):
            if a[i]=="1":
                l.append(i+1)
        m=0
        for i in range(len(l)-1):
            m=max(m,abs(l[i]-l[i+1]))
        return m
