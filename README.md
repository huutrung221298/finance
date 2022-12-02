# finance-app
## A app track buying, selling stock

## Before run a this app, we have to apply api_key = pk_e4fa82173c38449e8c817f8c02f50248 from IEX cloud. The app will recieve JSON data (name, price and symbol) from IEX

## Feature of the app:

### In finance.db I create 2 tables. First one is user which have id, user_account, hash. The second one is transactions which have shares, symbol of company, price of the stock


### Login
> the app will request a account to access to another feature. User have to go to register page to fill the form to register. User data will be stored in finance.db. Their password will be encrypted to token by Hash function

### index page:
> User will see the stocks that they have, the value of all their stocks and the remaining cash. All this data from the page are taken from finance.db

### quote page:
> In this page user can check the stock by its symbol. This page will be showed the company's name, price of stock. The data is taken from IEX 

### Buy page:
> User need to fill to the form that what stock they want to by and how many stock

### Sell: 
> User can choose stock in selection form then sell 

### History:
> Where we can see our transactions
