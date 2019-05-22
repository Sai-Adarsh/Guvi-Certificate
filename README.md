# Guvi Certificate Generator from CSV
![alt text](/examples/img/1.png)

### (Only for windows)
## Install Xampp

* XAMPP is an easy to install Apache distribution containing MariaDB, PHP, and Perl. Just download and start the installer. It's that easy.
Download from [here](https://www.apachefriends.org/download.html)

## Instal Composer

* The installer will download composer for you and set up your PATH environment variable so you can simply call composer from any directory.

Download and run [Composer-Setup.exe](https://getcomposer.org/Composer-Setup.exe) - it will install the latest composer version whenever it is executed.

## Clone

* Clone the repo\
``` git clone https://github.com/Sai-Adarsh/ReportCard-Guvi``` \
``` cd ReportCard-Guvi```

## Configuring CSV & HTML

* Copy the desired column header (e.g: **Name, Codekata**) from **sample.csv** and replace it inside desired ```{{ }}```. e.g: ```**{{ Name }}, {{ Codekata }}**``` inside **sample.html**.
* Make sure there is no space in column headers\
**e.g:** \
```CodeKata_Score ✔️```\
```CodeKata Score ❌```\
**e.g:** \
![alt text](/examples/img/example.png) 

## Run

* Double click ```run.bat```. this will install the composer dependencies
* Double click ```runthis.bat```. this will start generating report cards inside **output/** folder


