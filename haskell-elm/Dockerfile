FROM fpco/stack-build:lts-5.3_20160214_1258
RUN apt-get update -y && apt-get install -y nodejs npm
RUN npm install -g n
RUN n 4.0.0
RUN npm install -g elm@0.16.0 gulp@3.9.0 bower@1.7.7
RUN node --version && npm --version && stack --version && elm-make --version 2>&1 >/dev/null | head -n1
