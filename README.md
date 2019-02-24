# ETL-nifi
Work on ETL(pipeline)
# alter column sql script in database for type cast
ALTER TABLE dallas_budget ALTER COLUMN BUDCURR TYPE bigint USING (BUDCURR:: bigint);
