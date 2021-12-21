# personnal-assistant

docker run --user $(id -u):$(id -g) -it  -v $(pwd):/app --entrypoint rasa rasa/rasa init


 docker run --user $(id -u):$(id -g) -it  -v $(pwd):/app --entrypoint rasa rasa/rasa shell