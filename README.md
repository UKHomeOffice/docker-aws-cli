# docker-aws-cli

A simple aws cli client

Usage

docker run \
--env AWS_ACCESS_KEY_ID=<<YOUR_ACCESS_KEY>> \
--env AWS_SECRET_ACCESS_KEY=<<YOUR_SECRET_ACCESS>> \
docker-aws-cli \
$AWS_COMMAND $ARGS
