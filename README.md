# retailstore

Application url - http://localhost:8085/discount (post)

user_type string's possible values - 
1 for employee 
2 for Affiliated get 10% discount
3 for being customer for 2 years
For any other user_type discount will not be applied.

request - {

"item_list" : [
{"item_type":"GROCERIES",
"item_name":"bread",
"quantity":"2",
"value":"5"
},
{"item_type":"NONGROCERIES",
"item_name":"chicken",
"quantity":"10",
"value":"50"
}
],
"user_type":1

}

response - Final bill after discount is 345
