# Assignment
Code Repository

Assignment #1 : Import of 1000 Account records to view the maximum Trigger processing size

AccountTrigger.apxt ,
AccountInsert.apxc ,
AccountTestClass.apxc ,
Debug Log.pdf

AccountTrigger.apxt   : Trigger on Account object will be called each time a record is inserted into the Account record and displays the                           size of the Trigger.new
AccountInsert.apxc    : Import of records could be done in different ways. First inserted 1000 records through Import Wizard and                                   Trigger.new.size() is 200. Second through Apex class which displays Trigger.new.size() as 200 which means trigger                         processing size is not more than 200 at once
AccountTestClass.apxc : Test class run to check the trigger.new.size()
Debug Log.pdf         : Debug messages to show the test results 

Assignment #2 : Online Currency Converter to display realtime exchange rates

CurrencyConversionController.apxc ,
CurrencyConvert.js  ,
CurrencyConvert.html  ,
CurrencyConvert.js-meta.xml ,
CurrencyConvert Output.pdf
