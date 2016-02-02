# jasperv2

Okay guys here's the basics.

You need to first have git on your local machine or else sudo apt-get install git should do.

Then navigate to the github repository(link) and you need to clone the rep into you local machine. To do so first create a new folder where you would like to keep all files.

copy the rep link which should to at the top right.

Navigate to the location where you want to save your work in terminal and type

        git clone "paste rep url" without quotes.

After you have the file locally you are free to make changes. Then once you have made your changes use

        git add .

this will add all files and Then

        git commit -m "with your message"

then write

        git remote add jasper "paste rep url here"s

and finally

        git push jasper master

We'll deal with merge conflicts later. Adios Muchachos.
