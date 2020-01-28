# pattern1
for i in range(n):
	for j in range(n):
  	if i+j==n//2 or i-j==-n//2+1 or j-i==-n//2+1 or i+j==n+(n//2-1):
      print('*',end='')
      else:
        print(' ',end='')
  print()
