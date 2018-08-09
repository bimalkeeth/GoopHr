FROM golang:1.10.1

ADD . /GoWorkPlaces/src/GoopHr/librarian

WORKDIR /GoWorkPlaces/src/GoopHr/librarian

RUN go install /GoWorkPlaces/src/GoopHr/librarian

ENTRYPOINT /go/bin/librarian

EXPOSE 9000