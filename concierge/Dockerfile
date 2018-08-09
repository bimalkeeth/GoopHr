FROM golang:1.10.1

ADD . /GoWorkPlaces/src/GoopHr/concierge

WORKDIR /GoWorkPlaces/src/GoopHr/concierge

RUN go install /GoWorkPlaces/src/GoopHr/concierge

ENTRYPOINT /GoWorkPlaces/src/GoopHr/concierge

EXPOSE 9000