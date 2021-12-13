# English

## What is it?

Ansible modules for PostgreSQL - plain drop-in for your project.

## What is this for?

If you ever had to install psycopg2, you've definitely came across that dependency hell: libraries, libraries and libraries - tons of them. This project nulls out said dependency hassle: everything works out-of-the-box, you don't have to install anything. The guest star here is "pg8000": pure-Python PostgreSQL driver, with minor modifications to support its loading and usage by Ansible.

## Requirements

* CentOS/RHEL 7.x;
* Ansible >=2.9.x;
* Python >=3.6.x;
* PostgreSQL >=10.x (this was debugged with Postgres 12, though)

## Quick start guide

1. Copy to your project directory:
   1. playbooks/library/*
   2. playbooks/module_utils/pg8000/*
   3. playbooks/module_utils/scramp/*

2. You're done, please don't forget to perform a wild dance (well, latter was a joke, just in case :-)

## How to send a donation to the author

If you want to thank the author - [this is a donate link](https://yoomoney.ru/to/410011277351108). Any sum is happily accepted. 

## Legal information

This project is conceived and performed by me, Sergey Pechenko, on my own will, out of working hours, using own hardware. 

Copyright: (С) 2021, Sergey Pechenko

This project includes the changes in the "postgres.py" Ansible module, which has own copyright:

(c) Ted Timmons <ted@timmons.me>, 2017 (BSD-licensed)

Other Ansible modules included with or without my changes carry their own licenses and copyright - please see the exact module for author names

This project also uses MIT-licensed components as follows: 

* pg8000 (c) 2007-2009, Mathieu Fenniak 

* scramp (C) 2019 Tony Locke 

Portions for these components that provide possibility for Ansible to load and run them are also (C) 2021, Sergey Pechenko. 

## License

GPLv3+ (please see LICENSE)

## Contact

You can ask your questions about this plugin at the [Ansible chat](https://t.me/pro_ansible), or [PM me](https://t.me/tnt4brain) 


