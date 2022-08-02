node {
    checkout scm
    sh './mvnw -B -DskipTests clean package'
    docker.build("myorg/myapp").push()
}