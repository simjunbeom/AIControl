# AIControl

## 파이썬3 프로그램 튜토리얼 모음 

## 변수 유형

counter = 100          # 정수 할당
miles   = 1000.0       # 부동 소수점 


print (counter)
print (miles)

## 파이썬 문자열 

str = 'Hello World!'

print (str)          # 전체 문자열 
print (str[0])       # 문자열의 첫 번째 문자
print (str[2:5])     # 3번째부터 5번째까지 문자
print (str[2:])      # 세 번째 문자부터 시작하는 문자열
print (str * 2)      # 문자열을 두 번
print (str + "TEST") # 연결된 문자열

## 파이썬 목록

list = [ 'abcd', 786 , 2.23, 'john', 70.2 ]
tinylist = [123, 'john']

print (list)          # 전체 목록
print (list[0])       # 목록 첫 번째 
print (list[1:3])     # 목록 첫 번째 에서 세 번째  
print (list[2:])      # 세 번째 부터 
print (tinylist * 2)  # 목록을 두 번
print (list + tinylist) # 연결된 목록

## 파이썬 튜플

tuple = ( 'abcd', 786 , 2.23, 'john', 70.2  )
tinytuple = (123, 'john')

print (tuple)           # 튜플 전체
print (tuple[0])        # 튜플의 첫 번째
print (tuple[1:3])      # 튜플 첫 번째 부터 세 번째
print (tuple[2:])       # 튜플 첫 번째 에서 세 번째  
print (tinytuple * 2)   # 튜플을 두 번
print (tuple + tinytuple) # 연결된 튜플

## 파이썬 dictionary

dict = {}
dict['one'] = "This is one"
dict[2]     = "This is two"

tinydict = {'name': 'john','code':6734, 'dept': 'sales'}

print (dict['one'])       # dict['one'] 입력 
print (dict[2])           # dict[2]  입력
print (tinydict)          # tinydict 입력
print (tinydict.keys())   # tinydict 에서 키만 입력 
print (tinydict.values()) # tinydict 에서 values 만 입력 
