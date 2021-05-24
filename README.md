# FirstProject
I take courses on dataquest and each chapter ends with a challenge of which here is the first theme


Profitable App Profiles for the App Store and Google Play Markets
We only develop apps that are free to download and install, and our main source of revenue is in-app ads. This means that our revenue for a given app is primarily influenced by the number of users who use our app - the more one user sees and interacts with the ads, the better. Our goal for this project is to analyze the data to help our developers understand what kind of apps are likely to attract more users.

In [26]:
from csv import reader

####The Google Play data Set######

opened_file = open('googleplaystore.csv', encoding = 'utf8' )
read_file = reader(opened_file)
android = list(read_file)
android_header = android[0]
android = android[1:]

####The Apple Store data Set######

opened_file = open('AppleStore.csv', encoding = 'utf8')
read_file = reader(opened_file)
ios = list(read_file)
ios_header = ios[0]
ios = ios[1:]

# La suite sur le fichier du même nom 
