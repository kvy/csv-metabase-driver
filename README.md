# csv-metabase-driver
A CSV [metabase](https://www.metabase.com) driver based on incredible [csvjdbc](http://csvjdbc.sourceforge.net) driver. I've been [modified it](https://github.com/Markenson/csvjdbc4metabase) to work with metabase.

# Installation
Put [this file](https://github.com/Markenson/csv-metabase-driver/releases/download/1.1.0/csv.metabase-driver.jar) on your metabase/plugins directory and restart Metabase. You'll see a CSV driver option on database creation.

# How to configure it
Check [how to load a CSV file by filesystem](https://github.com/Markenson/csv-metabase-driver/issues/1) and [how to load a CSV file by HTTP](https://github.com/Markenson/csv-metabase-driver/releases/tag/1.1.0) for more information.

# If you need built it

[Install lein](https://leiningen.org)

git clone https://github.com/Markenson/csv-metabase-driver.git

cd csv-metabase-driver/csv

lein install

get the build at csv-metabase-driver/csv/target

