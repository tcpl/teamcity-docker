FROM alpine:latest

RUN apk add --no-cache curl

CMD echo "sleeping for 60 secs"; sleep 60; echo "hitting BrowserStack"; curl https://www.browserstack.com; echo "sleeping for 60 secs"; sleep 60;