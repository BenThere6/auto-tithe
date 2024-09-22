# Auto Tithe Payer

## Description
Automatically make tithing donations to the Church of Jesus Christ of Latter-day Saints

## Instructions
1. Clone repository
2. Install packages using `npm i`
3. Create .env file, using the example found in .env.EXAMPLE
4. Run `node tithing`
    * This command will donate the default amount of $1. To donate a custom amount, simply add that number to the end of the command: `node tithing 150`.

**You can also import the function automateDonation into another project to fully automate the process.**
1. Include the import line
    * `const { automateDonation } = require('./tithing');`
2. Call the function
    * `await automateDonation('150');`

*Note that the tithing amount needs to be a string*