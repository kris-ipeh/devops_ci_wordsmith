FROM golang

COPY dispatcher.go /app/dispatcher.go
COPY static/ /app/static/

WORKDIR /app/
RUN go build dispatcher.go
CMD ./dispatcher
EXPOSE 80
