stage 'Dev'
node {
    checkout scm
    def mvnHome = tool 'Maven'
    sh "${mvnHome}/bin/mvn clean install"
}
