allready4v-docker-wordpress
======================

Out-of-the-box Wordpress docker image


Usage
-----

To create the image `allready4v/wordpress`, execute the following command on the allready4v-docker-wordpress folder:

	docker build -t allready4v/wordpress https://github.com/allready4v/docker-wordpress.git

You can now push your new image to the registry:

	docker push allready4v/wordpress


Running your Wordpress docker image
-----------------------------------

Start your image:

	docker run -d -p 80:80 allready4v/wordpress

Test your deployment:

	curl http://localhost/

You can now start configuring your Wordpress container!

