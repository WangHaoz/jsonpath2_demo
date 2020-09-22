### **GetJsonValue**
pip install GetJsonValue

from GetJsonValue import jsonvalue

user_dict = {
        "sites":
            [
                { "name":"runoob" , "url":"www.runoob.com" },
                { "name":"google" , "url":"www.google.com" },
                { "name":"weibo" , "url":"www.weibo.com" }
            ]
    }
    
r = jsonvalue.get(user_dict,'url')

print(r)

output: ['www.runoob.com', 'www.google.com', 'www.weibo.com']