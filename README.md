# Multiclipboard

Keeps track of multiple pieces of text for the clipboard

The program saves each element of text with its own keyword

EX: mcb.pyw save address
    this will save whatever is on your clipboard with the keyword address

Process:
    Saving: 
      mcb.pyw save keyword
      access the clipboard contents and pair it with its keyword in a database
    Database:
      use file IO and save each item as a dictionary
    Accessing Saved Keywords:
      Run the program likewise: python mcb.pyw keyword      < That will change the contents of your clipboard
      

