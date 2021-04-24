# calculadoraSimples
#Calculadora apenas com + , - , *  e / . 


num1 = 0
num2 = 0
res = 0
oper = ''

num1 = int(input('digite num 1: '))
oper = input('digite a operação: ')
num2 = int(input('digite num 2: '))


if oper =='+':
  res= num1 + num2
elif oper =='-':
  res = num1 - num2  
elif oper =='*':
  res = num1 * num2
elif oper =='/':
  res = num1 / num2 
else:
  res = 'operação inválida'  
print ( str(num1)+ ' ' + str(oper)+ ' ' + str(num2) + ' = ' + str(res) ) 
