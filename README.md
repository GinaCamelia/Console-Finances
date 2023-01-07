# Console-Finances
Creating code for analysing the financial records of a company

## Description 

I have a list of financial data with the profit or loss for each month. We want to find out some information about this data using for loops and if statements.

**Thought Process:**

To find the **net profits or losses** over the entire period, we can do the following:

* Initialize a variable to store the total profit or loss.
* Start a for loop that will go through each month's data.
* Inside the for loop, add the current month's profit to the total profit or loss.
* After the for loop is finished, output the total profit or loss. If the total is positive, it is a net profit. If the total is negative, it is a net loss.

To find the **average change** in profits from month to month, we can do the following:

* Initialize a variable to store the total change in profits.
* Start a for loop that will go through each month's data, starting at the second month (since there is no change in profits for the first month).
* Inside the for loop, get the current month's profit and the previous month's profit.
 * Calculate the change in profits between the current month and the previous month.
* Add the change in profits to the total change.
* After the for loop is finished, divide the total change in profits by the number of changes to get the average change in profits.
* Output the average change in profits.

To find the **greatest increase** and **greatest decrease** in profits, we can do the following:

* Initialize variables to store the date and amount of the greatest increase and decrease in profits.
* Start a for loop that will go through each month's data, starting at the second month (since there is no change in profits for the first month).
* Inside the for loop, get the current month's profit and the previous month's profit.
* Calculate the change in profits between the current month and the previous month.
* If the change in profits is greater than the current greatest increase in profits, update the greatest increase variables to store the date and amount of the current change in profits.
* If the change in profits is less than the current greatest decrease in profits, update the greatest decrease variables to store the date and amount of the current change in profits.
* After the for loop is finished, output the date and amount of the greatest increase and decrease in profits.


## Installation

N/A

## Usage

Open the html file and inspect the console. The console should show the following information:

## Credits

N/A

## License

Check the LICENSE file for details in the repository