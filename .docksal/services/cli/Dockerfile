# Use a stock Docksal image as the base
FROM docksal/cli:2.1-php7.1

# Install hugo 0.34
RUN wget -q https://github.com/gohugoio/hugo/releases/download/v0.63.1/hugo_extended_0.63.1_Linux-64bit.deb -O /tmp/hugo.deb \
    && dpkg -i /tmp/hugo.deb
