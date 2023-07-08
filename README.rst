``KAMABAY`` WHOIS (updated by JAY)
--------------------------
**Installation**
- Just updated the instructions in case you want to use my updated code.
.. code :: python

        #windows
        pip install git+https://github.com/techdjay/ipwho
        #linux & termux
        pip install git+https://github.com/techdjay/ipwho
        # OR
        $ git clone https://github.com/techdjay/ipwho 
        $ cd ipwhois && pip3 install requests
        $ clear && python3 main.py
        

``URL`` `https://github.com/techdjay/ipwho`_

**using command line type** ``ipwho <ip>`` see below the example

- Please Note: Updated to show only the below instructions as most people want this output regularly:
----------------------------------------
# ipwhois 8.8.8.8
IP: 8.8.8.8
Organization: Google LLC
ISP: Google LLC
----------------------------------------

**using import package** ``from ipwho import ipwho``
.. code :: python

        >>> from ipwho import ipwho
        >>>
        >>> ipwho('0') # zero string default local IP
        {
        "asn":"AS4818",
        "city": "Batu Pahat",
        "completed_requests": 2,
        "continent": "Asia",
        "continent_code": "AS",
        "country": "Malaysia",
        "country_capital": "Kuala Lumpur",
        "country_code": "MY",
        "country_flag": "https://cdn.ipwhois.io/flags/my.svg",
        "country_neighbours": "BN,TH,ID",
        "country_phone": "+60",
        "currency": "Malaysian Ringgit",
        "currency_code": "MYR",
        "currency_plural": "Malaysian ringgits",
        "currency_rates": "4.146",
        "currency_symbol": "RM",
        "ip": "115.164.173.247",
        "isp": "DiGi Telecommunications Sdn Bhd., Digi Internet Exchange",
        "latitude": "1.849442",
        "longitude": "102.9288341",
        "org": "DiGi Telecommunications Sdn Bhd., Digi Internet Exchange",
        "region": "Johor",
        "success": true,
        "timezone": "Asia/Kuala_Lumpur",
        "timezone_dstOffset": "0",
        "timezone_gmt": "GMT +8:00",
        "timezone_gmtOffset": "28800",
        "timezone_name": "Malaysia Time",
        "type": "IPv4",
        }



``@copyright 25052021``

``mail`` `lexyong66@gmail.com`_ 

.. _lexyong66@gmail.com : lexyong66@gmail.com
.. _https://pypi.org/project/kamabay-ipwhois/ : https://pypi.org/project/kamabay-ipwhois/
