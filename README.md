def test(clair,cle):
    L=["A","B","C","D","E","F","G","H","I","J","K","L","M","N","O","P","Q","R","S","T","U","V","W","X","Y","Z"]
    C=list(clair.upper())
    A=0
    for a in range(len(C)):
        if C[A] not in L:
            C.pop(A)
            A-=1
        A+=1
    print(C)
    []
    
    def rsa(clair,e=23,n=52635239):
    M=''
    L=len(str(clair))
    for a in range(L):
        M+=str(ord(clair[a]))
    print(M)
