# python_json
json与python格式转换



import json
data=[{"name":"zh张agn","age":12},{"name":"李","age":11},{"name":"zasfdhagn","age":102}]
json_str=json.dumps(data,ensure_ascii=False)
print(type(json_str))
print(json_str)

s='[{"name": "zh张agn", "age": 12}, {"name": "李", "age": 11}, {"name": "zasfdhagn", "age": 102}]'
l=json.loads(s)
print(type(l))
print(l)
