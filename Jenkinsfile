pipeline {
agent any
Stages{
stage('build')
{
echo 'running build automation'
{
sh './gradlew build --no-deamon'
archiveArtifacts artifacts: 'dist/Trainschedule.zip'

}
}



}

}
