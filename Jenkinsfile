node {
    def rtGradle = Artifactory.newGradleBuild()

    stage('Clone sources') {
        git url: 'https://github.com/NatalliaKhadunai/JenkinsPipeline'
    }

    stage('Gradle build') {
        rtGradle.run tasks: 'build'
    }
}