
# mern-book-store-inventory-server
 
## Vercel config
```
{
    "version": 2,
    "builds": [
        {
            "src": "./index.js",
            "use": "@vercel/node"
        }
    ],
    "routes": [
        {
            "src": "/(.*)",
            "dest": "/",
            "methods": ["GET", "POST", "PUT", "PATCH", "DELETE", "OPTIONS"]
        }
    ]
}
```
#   s u s t a i n a b l e - b a c k e n d  
 #   s u s t a i n a b l e - b a c k e n d  
 