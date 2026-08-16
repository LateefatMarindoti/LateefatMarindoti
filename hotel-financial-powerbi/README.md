# Hotel Financial Performance Report

Power BI data modelling project.

## The question

Financial data arrived as 24 separate monthly files in more than one currency. That is a reporting problem before it is an analysis problem.

## Approach

1. Folder import in Power Query to combine the monthly files
2. Built a custom date dimension in M rather than relying on auto date/time
3. Applied currency conversion against a rate table
4. Modelled the result as a star schema with proper dimension tables
5. Built the report layer on top

## Tools

Power BI, Power Query, M, DAX

## Files

Add here: the .pbix file, screenshots of the report pages (so recruiters can see it without opening Power BI), and the M code for the date table.
