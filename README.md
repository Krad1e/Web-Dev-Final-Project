<h1>How to use: </h1> 

1. Install dependencies (check packages.json line 12 for installed dependencies)
>npm install "dependency name"  
    
<b>Example:</b>  
>npm install express

2. Create and modify .env file in program root directory so that:
>USER = "YOUR EMAIL"  
>PASS = "YOUR PASSWORD"

3. Modify:  
server.js line 22: change to reflect your database name.  
index.ejs line 16: change to reflect your email address.  
index.ejs lines 27-44: modify to reflect your database tables and rows.

4. Run server with: 
>npm start