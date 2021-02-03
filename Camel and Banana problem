tb=int(input('bananas at starting='))
d=int(input('distance to be covered='))
load_capacity=int(input('max load capacity of camel='))
lb=0
start=tb
for i in range(d):
    while start>0:
        start=start-load_capacity
        if start==1:
            lb=lb-1
        lb=lb+2
    lb=lb-1
    start=tb-lb
    if start==0:
        break
print(start)
