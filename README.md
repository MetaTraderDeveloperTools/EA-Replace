# EA-Replace
If you have multiple MetaTrader installations on one computer, running the same EA, you can automate EA replacement.


Development language: Visual Studio 2019 C#  
Platform: Windows OS

EAs are distributed simultaneously to all MetaTraders that exist on the computer on which this tool is run.
Even if multiple Windows accounts have been created and MetaTrader is used for each account, EAs can be distributed simultaneously to MetaTrader for all accounts.
MetaTrader versions 4 and 5 are supported.

Before executing the program, the following logic is in the DistributeEA() method of "main.cs".


    orgPath = "[Folder path from which to distribute]" + mqlVer;


The part corresponding to "[Folder path from which to distribute]" is rewritten to an arbitrary folder path, and the EA to be distributed simultaneously is stored in that folder.

If you have any questions or requests for modification, please contact us from the (MetaTrader Developer Tools)[https://metatrader25.wixsite.com/metatrader-developer] website.
