
# Multiverse Self-Study Project

A front-end project/api built in Angular, completed while participating in the Multiverse program


## Self-Study Plan

- Learn Angular by utilizing PluralSight and YouTube lessons/tutorials
- Design project in line with Amex team needs
- Responsive and clear UI/UX
- Verify CRUD functionality across project


## Lessons Links

[YouTube Playlist](https://youtube.com/playlist?list=PLtgniFeQ_KZvK-sHoQ21kjPzHrGGdmViA) - Scroll to the bottom to see the related lessons and tutorials

[PluralSight Course on Angular](https://app.pluralsight.com/library/courses/angular-2-getting-started-update/table-of-contents) - Angular introduction

[O'Reilly Lessons](https://www.oreilly.com/videos/angular-the/9781788998437/) - More Angular video lessons
## Project Features

**CRUD Functionality:** 
 - Browse all lists and individual products
 - Manage customer orders
 - Manage products within inventory

### POST

 - Create NEW order

```http
  POST /src/orders/new
```

 - Create NEW product

```http
  POST /src/products/new
```

### GET

 - Pull ALL products

```http
  GET /src/products/all
```
 - Pull product by ID

```http
  GET /src/products/:sku
```

 - Pull ALL orders

```http
  GET /src/orders/all
```

 - Pull order by ID

```http
  GET /src/orders/:uuid
```

 - Pull ALL users

```http
  GET /src/users/all
```

 - Pull users by ID

```http
  GET /src/users/:id
```

### PUT

 - Edit product by ID

```http
  PUT /api/products/:sku/edit
```

 - Edit user by ID

```http
  PUT /api/users/:id/edit
```

 - Delete product by ID

```http
  PUT /src/products/:sku/delete
```

 - Delete user by ID

```http
  PUT /api/users/:id/delete
```
### Acknowledgements

 - [Readme Editor](https://readme.so/editor) - Simplified the README creation process
 - [Angular Materials](https://material.angular.io/) - Component Library
 - [Programming with Mosh](https://www.youtube.com/c/programmingwithmosh) - Fantastic content creator on YouTube, really helped me out

#
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://studiobebop.games)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haley-tobias-019a84132/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/mrsallhershots)

