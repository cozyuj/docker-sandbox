<<<<<<< HEAD
FROM golang:1.24
=======
# Multi-stage build::
# 하나의 Dockerfile내에서 여러개의 FROM 명령어를 사용해 
# 여러 빌드 단계를 정의하는 기능

FROM golang:1.24 AS build
>>>>>>> 97513ac (Update Dockfile for Multi-stage)
WORKDIR /src
COPY ./main.go .
RUN go build -o /bin/hello ./main.go
CMD ["/bin/hello"]
<<<<<<< HEAD
=======


FROM scratch
COPY --from=build /bin/hello /bin/hello
CMD ["/bin/hello"]
>>>>>>> 97513ac (Update Dockfile for Multi-stage)
