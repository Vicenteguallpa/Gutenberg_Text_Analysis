FROM python:3

COPY /bin /bin

COPY /python /python

ENV CONTAINER_VOL container_volume

ENV JEKYLL_GEN_INPUT jekyll_generator_input

ENV JEKYLL_GEN_OUTPUT jekyll_generator_output

ENV VOYANT_GEN_OUTPUT voyant_generator_output

VOLUME [/${CONTAINER_VOYANT_GEN_VOL}]

WORKDIR /python

CMD jekyll_gen_script.sh
