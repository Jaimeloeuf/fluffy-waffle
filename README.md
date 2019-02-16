# README file for my Learning Elixir Repo

I am using elixir on windows, and to simplify things I use docker to run elixir, so I do not have to deal with the installations and all. Below is the command I use

- To get the full elixir package (Note that it is pretty huge, about 1GB)
	- docker pull elixir
- To get the elixir image based on alpine linux (Alot smaller, about 90MB)
	- docker pull elixir:alpine
- To run the elixir REPL directly with a interactive tty
	- docker run -it elixir