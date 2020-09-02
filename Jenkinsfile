node('master') {
    // some block
stage('preparation') {
    // some block
git 'https://github.com/jglick/simple-maven-project-with-tes ts.git'
}
stage('Build') {
    // some block
withMaven(maven: 'M3') {
    // some block
sh label: '', script: 'mvn -Dmaven.test.failure.ignore clean package'
}
}
}
