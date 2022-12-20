>>>>> Page 0
> Welcome page
// Localhost // "localhost:1607"
// LiveUrl // "https://healingblues-server.onrender.com/"

>>>>> Page 1
> List of categories
// Localhost // "localhost:1607/category"
// LiveUrl // "https://healingblues-server.onrender.com/category/"

>>>>> Page 2
> List of services
// Localhost // "localhost:1607/services"
// LiveUrl // "https://healingblues-server.onrender.com/services/"

> Service details on the basis of category
// Localhost // "localhost:1607/listing?category_id=1"
// LiveUrl // "https://healingblues-server.onrender.com/listing?category_id=1"

> Sort (Low to High)
// Localhost // "localhost:1607/sortfromlow"
// LiveUrl // "https://healingblues-server.onrender.com/sortfromlow/"

> Sort (High to Low)
// Localhost // "localhost:1607/sortfromhigh"
// LiveUrl // "https://healingblues-server.onrender.com/sortfromhigh/"

>>>>> Page 3
> Place orders
// (post) // "localhost:1607/placeOrder"
// (body) // 
{   "name":"Chhuti Mistry",
    "email":"chhuti246@gmail.com",
    "address":"Azad Hind Nagar",
    "phone":"+918170974173",
    "cost":"2500",
    "status":"pending"
}

> See all placed orders
// Localhost // "localhost:1607/viewOrder"
// LiveUrl // "https://healingblues-server.onrender.com/viewOrder/"

> Get order details on the basis email address
// Localhost // "localhost:1607/viewOrder?email=chhuti246@gmail.com"
// LiveUrl // "https://healingblues-server.onrender.com/viewOrder?email=chhuti246@gmail.com"