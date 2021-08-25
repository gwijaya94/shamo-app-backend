User 
1. username
2. phone_number
3. roles

Product Categories
1. name

Product
1. name
2. price
3. description
4. tags
5. Kategori product [FK]

Gallery Product
1. Product [FK]
2. url

Transaction
1. User [FK]
2. address
3. metode bayar
4. total price
5. shipping price
6. status

Detail Transaction
1. User [FK]
2. Product [FK]
3. Transaction [FK]
4. qty