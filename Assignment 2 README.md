# Assignment 2: Sales Team Data Processor

## Overview:
This program aims to gather, sort, and provide statistics for a sales team. The application is designed as either a Console Application, where users can input data about various salespersons and receive insights on sales figures.

## Requirements:

### Input:
- Name of the salesperson.
- Personal identification number.
- District where they work.
- Number of articles sold during the period.

### Output:
- The sorted list of salespeople based on the number of articles sold.
- A summary showing the number of salespeople in specific sales ranges: below 50, 50-99, 100-199, and above 199 articles.

### Additional Features:
- The program should display results on the screen and also write them to a file.
- Ensure the program uses suitable methods (functions) for various tasks.
- Provide algorithm representation, possibly in flowchart or pseudocode format.
- The results should be summarized right after listing the sellers for a particular level, as shown in the example.

## How to run:

### Console Application:
1. Navigate to the project directory.
2. Run the .exe file for the console application.
3. Follow the on-screen instructions to input the salesperson details.
4. Check the file with the output in the same directory as the .exe.

## Example Output:

-----------------------------------------
        Sales Data Processor
-----------------------------------------

Enter number of salespeople to register: 3

--- Salesperson 1 ---
Enter Name: Kalle Anka
Enter Personal Identification Number: 4503038990
Enter District: Piteå
Enter Number of Articles Sold: 173

--- Salesperson 2 ---
Enter Name: Musse Pigg
Enter Personal Identification Number: 3502038964
Enter District: Boden
Enter Number of Articles Sold: 202

--- Salesperson 3 ---
Enter Name: Snobben
Enter Personal Identification Number: 7805055673
Enter District: Luleå
Enter Number of Articles Sold: 203

Processing data...

-----------------------------------------
            Processed Sales Data
-----------------------------------------

Name          Persnr          District   Articles Sold
------------------------------------------------------
Kalle Anka   4503038990       Piteå      173
1 salesperson reached Level 3: 100-199 articles.

Musse Pigg   3502038964       Boden      202
Snobben      7805055673       Luleå      203
2 salespeople reached Level 4: Over 199 articles.

Data written to 'SalesDataOutput.txt' in the application directory.

Press any key to exit...

