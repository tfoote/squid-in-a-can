FROM debian:jessie
RUN apt-get -q update && apt-get -qy install iptables python
ADD manage.py /tmp/manage.py
CMD /tmp/manage.py
