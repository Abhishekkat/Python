Lambda function(Anonymous function)
inline function
lanbda argument:expression


#Simple function
def add_five(num):
 result = num + 1
 return result

#Lambda function
lambda_add_five = lambda x: x + 5
y = 10
print(lambda_add_five(y))

#concen
lambda_add_five = lambda x, y: x + 5
x=6
print(lambda_add_five(x,y))

con=lambda str1 , str2 : str1 + str2 
str1="hello"
str2="world"
print(con(str1,str2))

temp=0
max=lambda


lambda_max_two = lambda x,y : x if x>y else y

list1=[1,2,3,4]
sq=lambda x:x*x
sqli=list(map(sq,list))


Add two list using map()
list_a=[1,2,3,3,4]
list_b[5,6,7,7]
list_c=lambda x,y:x+y
sum=list(map(list_c,list_a,list_b)))
print(sum)


Add two list using reduce()
list=[1,2,3,4,4]
add_two_num=lambda x , y : x+y
result=functools.reduce(add_two_num,list)

#how to use filter using lambda
seq=[1,2,3,4,4,5,6,6]
filter_odd= lambda x : x%2!=0
result=list(filter(filter_odd,seq))
print(result)






