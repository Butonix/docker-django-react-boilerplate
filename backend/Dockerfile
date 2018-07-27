FROM alpine:3.7

RUN apk add --no-cache bash git nginx uwsgi uwsgi-python3 \
	&& pip3 install --upgrade pip

WORKDIR /source

COPY ./source/ .

EXPOSE 8000

CMD ["/source/entrypoint.sh"]
