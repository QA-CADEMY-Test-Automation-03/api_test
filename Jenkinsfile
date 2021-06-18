pipeline {
  agent any
  tools {
    gradle "gradle"
  }
  stages {
    stage("build") {
      steps {
        bat 'echo building'
      }
    }
    stage("test") {
      steps {
        bat 'gradle cucumber'
      }
    }
    stage("deploy") {
      steps {
        bat 'echo deploying'
      }
    }
  }
}
