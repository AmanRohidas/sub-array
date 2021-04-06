# sub-array
print all subarray
s = [2,7,5]
op = [s[i:j] for i in range(len(s)) for j in range(i+1,len(s)+1)]
print(op)
