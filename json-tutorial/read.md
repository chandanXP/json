#{"json objects": "values"}
1. JSON.parse(json)
2. parsed = JSON.parse(myJson)
#parsing element
3. parsed["isAdmin"] 
#parsing array element from json
4. parsed["shopItem"][2] 
#json inside an array 
"skills": ["python", "data science", {"jupyter": true}]
#parsing json inside an array
parsed["myobj"]["skills"][2]["jupyter"] 