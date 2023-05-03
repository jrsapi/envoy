FROM postgres:latest@sha256:5724544cdf4072f4a1e245571063d07a6ed5eef8e9f33dd177b89cc2a5fc1d06
COPY docker-healthcheck.sh /usr/local/bin/
HEALTHCHECK CMD ["docker-healthcheck.sh"]
