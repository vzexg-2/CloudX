# CloudX LOG
---------------------
*Error LOG:*

*TypeError*: a bytes-like object is required, not 'str'
    self._target(*self._args, **self._kwargs)
  File "/home/JCloudX/CloudX/CloudX", line 92, in attack
    s.sendto("GET /%s HTTP/1.1\r\n" % (url), (ip, int(port)))

*Exception in thread Thread-1*:
Traceback (most recent call last):
  File "/usr/lib/python3.9/threading.py", line 954, in _bootstrap_inner
    self.run()
  File "/usr/lib/python3.9/threading.py", line 892, in run
    self._target(*self._args, **self._kwargs)
  File "/home/juharisunshine/CloudX/CloudX", line 109, in flood_url
    user_agent += ' '.join([random.choice(v['name']) for k, v in USER_AGENT_PARTS['platform'].items()])
  File "/home/juharisunshine/CloudX/CloudX", line 109, in <listcomp>
    user_agent += ' '.join([random.choice(v['name']) for k, v in USER_AGENT_PARTS['platform'].items()])
KeyError: 'name'

----------------------


## What is CloudX?
CloudX is a DDoS tool that can pass through the https/http, CloudX has a chance of 23% to break ( pass through ) https protocol website, and 79% to pass through the http website protocol!

CloudX has a chance of 1.2% to destroy the https protocol website! here's an example of https website is https://sma1wiradesa.sch.id/

## What is HTTPS/HTTP?
Hypertext transfer protocol secure (HTTPS) is the secure version of HTTP, which is the primary protocol used to send data between a web browser and a website. HTTPS is encrypted in order to increase security of data transfer and 

HTTPS itself is a secure version of a protocol, but HTTP is not so website that still use HTTP protocol has a 55% chance of being attacked by DDoS

## CloudX Is under development 
CloudX is new and has many error so don't have much expectations about this program.

To run the script, type:

sudo apt-get update; sudo apt-get upgrade; git clone https://github.com/vzexg/CloudX; cd CloudX; ulimit -n 999999; sudo python3 CloudX

## Contact
sunshinexjuhari@protonmail.com
Whatsapp: +6282122932858
