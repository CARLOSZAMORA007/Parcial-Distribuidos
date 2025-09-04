FROM alpine:3.20

WORKDIR /app

RUN apk --no-cache add curl

COPY mensaje.txt /app/mensaje.txt

CMD ["cat", "mensaje.txt"]
