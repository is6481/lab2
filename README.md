Objectives
==========

In chapter 2 of our text, we discuss how to link strategy and business
analytics. Strategy is linked to analytics by considering what kinds of
metrics describe a successfully executed strategy. Once those metrics
are determined, we need to acquire the data, transform the data and,
finally, provide the data to the business in what the text calls a
“front-end” system.

### DVD Rental Business

This lab is the first of a three part exercise to link strategy and
analytics. For these exercises, we consider a fictional DVD rental
business. Back in the old days, DVD rental businesses existed as
stand-alone store fronts. (In the beginning, these stores rented
something called a VHS tape, but we’ll skip that part of ancient
history.) These businesses contained rows and rows of physical shelves
where customers could browse the different titles. Customers could then
rent the DVD for a period of three to five nights. To rent the DVD, the
customer was required to stand in something called a “line” behind other
people and have an employee of the store ring them up using a cash
register. The customer would then go home and watch their newly rented
DVD. The customer then returned the video within the rental period. If
the DVD was returned after the rental period, the customer would be
faced with fines for each night the video was out beyond the rental
period.

The corporate office of the DVD rental business has set a strategic goal
to **increase monthly per-customer revenue**.

We have the full relational database which includes the following
tables, a full schema can be found
[here](http://www.postgresqltutorial.com/postgresql-sample-database/).

-   actor – stores actors data including first name and last name.
-   film – stores films data such as title, release year, length,
    rating, etc.
-   film\_actor – stores the relationships between films and actors.
-   category – stores film’s categories data.
-   film\_category- stores the relationships between films and
    categories.
-   store – contains the store data including manager staff and address.
-   inventory – stores inventory data.
-   rental – stores rental data.
-   payment – stores customer’s payments.
-   staff – stores staff data.
-   customer – stores customers data.
-   address – stores address data for staff and customers
-   city – stores the city names.
-   country – stores the country names.

Instructions
============

For the strategic objective of **increasing monthly per-customer
revenue**, provide a written description of the following.

-   One or two initiatives you plan on executing to meet the objectives.
-   For each initiative list the following.
    -   Three or four metrics that will measure the effectiveness of the
        initiatives. (At least one needs to be **per-customer revenue**)
    -   Create targets for each metric.
-   Look through the list of tables and think through how they might
    need to be combined to create the metrics you have described.
    -   Write up a plan for how you need to combine the data.

Upload the writeup to Lab 2 in Canvas. Accepted formats are: docx, pdf,
html.
