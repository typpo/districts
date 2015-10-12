README.TXT file for the 2010 SAIPE State and County Estimates FTP Directory

I.    File Organization:

    The files in the estmod09 data directory contain estimates of poverty and income
    for 2010. There is one data file for each state with data for all 2010 statistics.  
    Additionally, there is also one file that includes the data for the US and each 
    state and county.  

  ------------------------------------------------------------------------

II.   File Names

        est10ALL.txt      (for US and all states and counties)
        est10US.txt       (for US with state data [but no county data])
        est10_[STATE].txt (for state with county data)

        where [STATE] = standard two-letter postal abbreviations.

  ------------------------------------------------------------------------

III.  Record Layout for Estimates Files

      Position   Variable

        1-  2    FIPS State code  (00 for US record)
        4-  6    FIPS county code ( 0 for US or state level records)

        8- 15    Estimate of people of all ages in poverty
       17- 24    90% confidence interval lower bound of
                   estimate of people of all ages in poverty
       26- 33    90% confidence interval upper bound of
                   estimate of people of all ages in poverty
       35- 38    Estimated percent of people of all ages in poverty
       40- 43    90% confidence interval lower bound of
                   estimate of percent of people of all ages in poverty
       45- 48    90% confidence interval upper bound of
                   estimate of percent of people of all ages in poverty

       50- 57    Estimate of people age 0-17 in poverty
       59- 66    90% confidence interval lower bound of
                   estimate of people age 0-17 in poverty
       68- 75    90% confidence interval upper bound of
                   estimate of people age 0-17 in poverty
       77- 80    Estimated percent of people age 0-17 in poverty
       82- 85    90% confidence interval lower bound of
                   estimate of percent of people age 0-17 in poverty
       87- 90    90% confidence interval upper bound of
                   estimate of percent of people age 0-17 in poverty

       92- 99    Estimate of related children age 5-17 in families in
                   poverty
      101-108    90% confidence interval lower bound of estimate of
                   related children age 5-17 in families in poverty
      110-117    90% confidence interval upper bound of estimate of
                   related children age 5-17 in families in poverty
      119-122    Estimated percent of related children age 5-17 in
                   families in poverty
      124-127    90% confidence interval lower bound of estimate of percent
                   of related children age 5-17 in families in poverty
      129-132    90% confidence interval upper bound of estimate of percent
                   of related children age 5-17 in families in poverty

      134-139    Estimate of median household income
      141-146    90% confidence interval lower bound of
                   estimate of median household income
      148-153    90% confidence interval upper bound of
                   estimate of median household income

          NOTE:  Columns 155-192 will be blank for all county-level
                 records.  These data are only available at the
                 national and state-level.

      155-161    Estimate of people under age 5 in poverty
      163-169    90% confidence interval lower bound of
                   estimate of people under age 5 in poverty
      171-177    90% confidence interval upper bound of
                   estimate of people under age 5 in poverty
      179-182    Estimated percent of people under age 5 in poverty
      184-187    90% confidence interval lower bound of
                   estimate of percent of people under age 5 in poverty
      189-192    90% confidence interval upper bound of
                   estimate of percent of people under age 5 in poverty

      194-238    State or county name
      240-241    Two-letter Postal State abbreviation
      243-264    A tag indicating the file name and date of creation

  ------------------------------------------------------------------------


