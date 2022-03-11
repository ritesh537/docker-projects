FROM httpd:2.4
RUN apt-get update && apt-get install git -y \
    && git clone https://github.com/rynrsts/simple-web-calculator.git \
    && rm -rf /var/lib/apt/lists/* 
WORKDIR simple-web-calculator
RUN mv index.html assets /usr/local/apache2/htdocs 
