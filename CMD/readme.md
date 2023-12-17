#CMD is the instruction that runs the container

# diff btw CMD and RUN

run command will execute at the time of image creation

CMD command will execute at the time of running conatiner.

There should be one CMD per docker file or else last CMD will take the preference.
