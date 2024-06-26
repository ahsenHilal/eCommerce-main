# eCommerce

How to run project :

- install docker: You need to start not only the backend, frontend, and admin but also the PostgreSQL database. 
                  This will allow you to access the data stored so far on localhost:8080.
- open terminal
- cd <path-to-project-folder>
- run docker-compose up
- terminate with docker-compose down
- for rebuild run docker-compose up --build

x
How to test 
- open terminal 

Frontend:
- run "docker exec -it ecommerce-frontend-1 npm test"

Admin2: ("e-commerce-admin" doesnt work, please only test "e-commerce-admin2")
- run " docker exec -it   ecommerce-admin-1  npm test "

Backend:
- run " docker exec -it ecommerce-backend-1 npx jest --coverage"


// Aufsetzen DB 

//Dockercontainer starten
Run docker-compose up --build

User Stories:
1. Customer Login 
2. Customer Registration
3. As a customer I can search for products
4. As a customer I can choose a product, add cart and buy it
5. As an admin I can show coupons
6. As an admin I can add new coupons
7. As an admin I can delete coupons
8. As an admin I can edit coupons
9. As an admin I can add new products
10. As an admin I can show product list
11. As an admin I can delete products
12. As an admin I can edit products
13. As an admin I can show categories
14. As an admin I can delete category
15. As an admin I can add new category
16. As an admin I can edit category
17. As an admin I can show colections
18. As an admin I can delete collections
19. As an admin I can add new collection
20. As an admin I can edit collections