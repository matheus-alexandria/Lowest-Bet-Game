<div style="text-align: center;">
<img src="https://user-images.githubusercontent.com/38626385/169737003-c9f8626e-6a67-49a2-8bbf-b5eedf2ea422.gif" width=200>
</div>

# The Lowest Bet Game

The server side of a simple game where an item enters auction with a limited time and everybody can make anonymous bets, in the end the lowest bet
that is unique between the bets done takes the item!

This server was done as a the first activity to a subject in college.
</br></br>

## To use this API repository:

First you must create a copy in your files and inside the terminal and run:
```
npm install
```

or

```
yarn
```

</br>

A simples DataBase is being build with the ORM Prisma. To create your own database and run the code you must create a .env file and complete with the needed variables shown in the example file. You can find more about the Prisma configuration in this page: [Prisma Getting Started](https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases/connect-your-database-typescript-postgres).


## Routes:

### Auctions

The auctions are created with an item to be auctioned and a date to end it, until this end date is met the players can make secret bets to it, that are related to that auction, when the time is done, you can return the winner bet.

