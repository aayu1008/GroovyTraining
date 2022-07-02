pipeline {
  agent any
  stages{
    stage(Hello){
      steps{
        println 'this is a build pipeline demo'
      }
    }
    stage(DevBuild){
      steps{
        println 'this is a dev build'
        git branch: 'main', credentialsId: 'GithubCreds', url: 'https://github.com/aayu1008/GroovyTraining'
      }
    }
    stage(SitBuild){
      steps{
        println 'this is sit build'
      }
    }  
    stage(UATBuild){
      steps{
        println 'this is a UAT build'
      }
    }
    stage(ProdBuild){
      steps{
        println 'this is a prod build'
      }
    }
  }
}
