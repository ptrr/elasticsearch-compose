# Elasticsearch

## Setup with Docker

There are only a few steps to setup Elasticsearch with Docker and Toolbox. 

Follow these steps:

* Download Docket-Toolbox from [here](https://www.docker.com/toolbox).
* Install Docker-Toolbox
* Start-up Docker-Quickstart-Terminal, this will setup all the necessary configuration and setup a base docker machine in VirtualBox (you don't need to download VirtualBox as it is included in the Docker-Toolbox)
* ``git clone https://github.com/ptrr/elasticsearch-compose``
* ``cd elasticsearch-compose``
* ``docker-machine env default``
* Now go into virtualbox and setup setup the port-forwarding guest to host on 9200
![](https://d1ro8r1rbfn3jf.cloudfront.net/ms_7147/yS1SuY9WKzc5ylNTor4ys1IRwGT73Q/dinghy%2B-%2BNetwork%2B2015-09-25%2B09-29-23.png?Expires=1443252584&Signature=YMxWjN3VW9TGBYp7hAj2NuuOy3mdHRkp0WR3wO7jJNpIb8GULBV-VuSLROiGpC2BVlpq-AXNq7fWw7K7bR5WtA8FqzMPuGjKI0aj51Sh9NiY-EjaVnoIHSX2PbhkZml1BU72CqbcMKtfhDBzy0SvsxfrnEtTppgiW3s9BXrveMVbilct7zmIRIzcHaQeJbRTBIdZWVigj37loA8gkSyhRXeSy1Bw4FQ9VvJL~RA7XNarGSl5XFhq-qmaQi6AmfslKNXkytKiXjOTHMcmOWb-TPQscGkjeqvkgq-XwMUtltpi3B8hkvvEVOPagsWg0FFelmwpx3N1YqDh3Iu8wELBTQ__&Key-Pair-Id=APKAJHEJJBIZWFB73RSA)
![](https://d1ro8r1rbfn3jf.cloudfront.net/ms_7147/2PgC8zHkkn0Qv95UQDPeUO48n03VEq/Monosnap%2B2015-09-25%2B09-29-33.png?Expires=1443252650&Signature=WBnVWvWl8SutWP9aLTRM6p70AupWnF97uJHBZay-aYT0viKN~HiYiBbsno1ToVIf4oCTtEIUjwpKb36dnw7qvs3KFTcl87SzJhBQXgYNZ7H20c0-n-BIRfhRyTGIDt6MGI6wRfQtjx6fv1MVBEUOIkz2jMkx3d1XGRkssJ~~oXXK4IhkB-FnanUGCZJS8T65wiOIu3d2Tp9iLIG6iUoFC3FeOd4p57IOH50nBWinn7CQJGhZuoZoaQM2FQ7P45J1MNOM1gDoFs0rbB9yVINlLi9G0FY4QQCS1TTzOnSO3MxyZFljD7okBgvq~2lOb-M-I6dsEjMSMjLfq4mZVjOwBg__&Key-Pair-Id=APKAJHEJJBIZWFB73RSA)

* ``docker-compose build``
* ``docker-compose start``
* Check if you can reach [localhost:9200](http://localhost:9200)
* Now you are ready to use Elasticsearch.

Now you are ready to use Elasticsearch.

## Already set up?
Use ``./start`` to start your docker elasticsearch server.
