# Python-detetime
# Python Dates
A date in Python is not a data type of its own, but we can import a module named datetime to work with dates as date objects.

Example:

Import the datetime module and display the current date:

    import datetime

    x = datetime.datetime.now()
    print(x)


# Date Output
When we execute the code from the example above the result will be:

    2023-02-11 19:01:50.453278

The date contains year, month ,day, hour, minute, second, and microsecond.

The datetime module has many methods to return information about the date object.

Here are a few examples, you will learn more about them later in this chapter:

Example:

Return the year and name of weekday:

    import datetime 

    x = datetime.datetime.now()

    print(x.year)
    print(x.strftime("%A))


# Creating Date Objects
To create a date, we can use the datetime() class (constructor) of the datetime module.

The datetime() class requires three parameters to create a date: year, month, day.

Example:

Create a date object:

    import datetime

    x = datetime.datetime(2020, 5, 17)

    print(x)


The datetime() class also takes parameters for time and timezone (hour, minute, second, microsecond, tzone), but they are optional, and has a default value of 0, (None for timezone).


