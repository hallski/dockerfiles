FROM elixir:latest

RUN apt update
RUN apt install -y nodejs npm inotify-tools

RUN mix local.hex --force
RUN mix archive.install hex phx_new 1.5.7 --force
