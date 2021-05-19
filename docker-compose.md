<h3>When to use --build flag and when to not in docker-compose up?</h3>
<p>
   When we update the dependencies in requirements.txt (considering it's a python project) or the dependencies in general, it is recommended to use docker-compose up --build as it runs all the commands in Dockerfile including the ones which include installing dependencies again.
</p>

<h3>What does "version:" in docker-compose.yml file mean?</h3>

<p>
  docker-compose has a couple of versions each using a slightly different format. With version specifying in the docker-compose.yml file, docker-compose knows which format to expect.
</p>
