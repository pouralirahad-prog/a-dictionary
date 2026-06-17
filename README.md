# a-dictionary
a dictionary--py


e2p={'hello':'salam','pencil':'medad','exatly':'daghiga'}
while True:
    define=input('enter')
    if define in e2p:
        print(e2p[define])
    elif define == '1':
        print(e2p.items())
        break


    else:
        mean=input('enter meaning to apped it')
        e2p[define]=mean
    
