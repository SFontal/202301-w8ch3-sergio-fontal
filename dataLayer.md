# DATA

## DATA LAYER

### Candy

- id
- name
- type
- flavour
- colour
- price
- image
- quantity
- isAvailable

### Customer

- id
- name
- email
- avatar
- adress
- phoneNumber
- token
- shoppingCart
- Orders
- isLogged

### Orders

- id
- customerData
- selledCandies
- totalPrice
- status

## DATA MODIFICATIONS

### Candy

- loadCandies
- addCandy
- deleteCandy
- modifyCandy
- setAvailability

### Customer

- addCustomer
- deleteCustomer
- modifyCustomer
- loginCustomer
- logoutCustomer

### Orders

- addOrder
- deleteOrder
- modifyOrder
