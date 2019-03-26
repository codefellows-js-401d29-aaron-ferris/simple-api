# simple-api

## Commands Line
* Categories post: `echo '{"name" : "book", "display_name": "libros", "description" : "you read them"}' | http :3000/categories`
* Categories GET: `http :3000/categories`
* Categories/id PUT: `echo '{ "name" : "yous a copy"}' | http put :3000/categories/2`
* Categories/id DELETE: `http delete :3000/categories/2`  
* Products GET: `http :3000/products` 
* Products  POST `echo '{"name" : "name of the wind", "category" : " libros", "display_name": "Kingkiller Chronicles: Name of the wind", "description" : "By Patrick Rothfuss. Really freaking good!"}' | http :3000/products`
* Products GET`http :3000/products`

* Products id PUT `echo '{ "name" : "yous a copy"}' | http put :3000/products/2`
* Products id  Delete : `http delete :3000/products/2`

I started on the swagger docs, and got stuck every time I tried to go through parameters. At first the yammel was throwing me for a loop. I couldn't see where things stopped and started, which made it hard.
After struggling a long time with the code, I finally hit some stuff on the api notes that I thought woud work, however it turned out it didnt. I wrestled over how exactly to put in my parameters