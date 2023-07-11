FROM ubuntu:22.04

ARG TZ=Etc/UTC

RUN apt-get update

# install apt-get
RUN apt-get install -y vim
RUN apt-get install -y tree
RUN apt-get install -y git
RUN apt-get install -y curl 

RUN apt-get install -y build-essential cmake meson
RUN apt-get install -y google-mock pkg-config cppcheck rapidjson-dev
RUN apt-get install -y libcpp-httplib-dev libgtest-dev libcurl4-openssl-dev 
RUN apt-get install -y libhowardhinnant-date-dev libgmock-dev

CMD ["/bin/bash"]