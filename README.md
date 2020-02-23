# Assignment
Code Repository

Assignment #1 : Import of 1000 Account records to view the maximum Trigger processing size

AccountTrigger.apxt
  ->  A before Insert Trigger on account, getting Trigger.new.size()
  ->  For import of 1000 records, trigger is processing records of 200 each
AccountInsert.apxc
  ->  getRecords() method that inserts 1000 Account records
AccountTestClass.apxc
  ->  Test class for Account Insertion
Debug Log
  ->  Debug message to view the trigger import size on bulk insertion
