FROM node:9.6.1

WORKDIR /source

ENV PATH /source/node_modules/.bin:$PATH

COPY ./source/ .

EXPOSE 3000

CMD ["/source/entrypoint.sh"]