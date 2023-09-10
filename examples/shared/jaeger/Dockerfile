FROM jaegertracing/all-in-one@sha256:38c13ea97a5e0c73a1188a137d106ca5a0da1df68a54ab38fce965d1a23b4e1c
HEALTHCHECK \
    --interval=1s \
    --timeout=1s \
    --start-period=1s \
    --retries=60 \
    CMD wget -q --header='Content-Type:application/json' -O - http://localhost:14269/health | grep "Server available"
