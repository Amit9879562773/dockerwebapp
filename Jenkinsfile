node {

    checkout scm

    docker.withRegistry('https://amitbapodara.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("amitbapodara/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
