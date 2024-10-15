n=4


# for row in range (1,n):
#     for col in range(1,row+1):
#         print(col,end='' )
#     print()    



# for row in range(2*n):
#     totalcolumninrow= 2*n - row if row > n else row
#     for col in range(1,totalcolumninrow):
#         print("*",end='')
#     print()



# for row in range (1,2*n):
#     totalcolumninrow = row
#     if row < n:
#         for col in range(1,totalcolumninrow):
#             print('* ',end='' )
#     else:
#         for col in range(1,2*n-row):
#             print('* ',end='' )    
#     print()








# n = 5  # Example value for n, you can change it as needed

# for row in range(1, 2 * n):
#     if row <= n:
#         # Print leading spaces
#         for space in range(n - row):
#             print(' ', end='')
#         # Print asterisks
#         for col in range(1, row + 1):
#             print('* ', end='')
#     else:
#         # Print leading spaces
#         for space in range(row - n):
#             print(' ', end='')
#         # Print asterisks
#         for col in range(1, 2 * n - row + 1):
#             print('* ', end='')
#     print()




n= 10
for row in range (1,n):
    for space in range(n-2*row):
        print(' ',end='')
    for col in range (1,row):
        print(row-1,end='')
    print()
