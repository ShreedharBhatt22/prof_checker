# Profanity_checker by Shreedhar Bhatt

A jupyter notebook to check the percentage of profanity in a given file<br>
Assumption : The given file has just tweets seperated by \n(new line)unicode.<br>

## Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following:

```bash
pip install better_profanity
```

## Steps to execute project
- Download zip file or clone the project.<br>
- Execute installations.<br>
- Open command prompt of that directory.<br>
- run the profanity_checker.ipynb file

##Logic
- Keeping it very simple there is a python library named better_profanity to check wether a text containg badwords or not , whenever some badword is deceted it converts that word into astrick(*) word.Hence, by calculating the number of astrick and the number of letters in that text , i find out the percentage of profanity. There is also a function which helps adding custom words to the list, i have implemented that too.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
