FROM alpine:latest

RUN apk add --no-cache curl

CMD echo "sleeping for 20 secs"; sleep 20; echo "hitting BrowserStack"; curl https://www.browserstack.com; echo "sleeping for 20 secs"; sleep 20;