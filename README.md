Django E-Commerce API

A product and order API that demonstrates different django features from basic ones to more advanced and complex ones. 
Note: This is purely a backend project, it has no frontend UI but can be connected to one.

The API includes features like creating users with specific and secure user-permissions for different requests and actions. i.e. Each user can only view their own orders, and only admins can view all users' orders.
It also includes more advanced features like filtering products by name and price, throttling to limit database hits per minute, and caching certain data with redis for a more efficient page loading and minimal database queries.

I also included the prefetch_related() method for many-to-many relationships resulting in better query optimization.
