# Utilizes a minimal Alpine Linux image as base
FROM alpine
LABEL manteiner="Ewerton"

# declares the arg and sets the default value
ARG MY_ARG="default value"

# sets the values received in the image 
# creation (or "default value" is none is provided) in the environment variable with the samne name of the argument
ENV MY_ARG=${MY_ARG}


# creates the image with a tag -t build-with-arg using the current directory (.)
# docker image build -t build-with-arg .


# To execute the container outputing the current MY_ARG value execute the following command:
# docker container run build-with-arg sh -c 'echo "$MY_ARG"'

# to execute the container setting and outputing "SomeValue" to the current MY_ARG variable
# docker container run -e MY_ARG=SomeValue build-with-arg sh -c 'echo "$MY_ARG"'