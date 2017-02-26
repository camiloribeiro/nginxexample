# nginxexample

This project adheres to the Contributor Covenant [code of conduct](CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code.

Simple nginx example to help a friend:

      - git clone git@github.com:camiloribeiro/nginxexample.git
      - cd nginxexample
      - docker-compose up

When running, just try the different routes:

      http://localhost/standard
      http://localhost/stream/stream
      http://localhost/sync
      http://localhost/sync/stream

You will need only docker and docker-compose to try it.

Change the configuration as it pleases you. Remember you have to kill the containers and start it again in order to aply any config changes. (yep, I will maybe fix it in the future)

If you have any questions about rest-shifter, the weird thing running the sinatra services, check it here: https://github.com/camiloribeiro/RestShifter
