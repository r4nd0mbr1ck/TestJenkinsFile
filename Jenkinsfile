@Library('test')_

def appsList = ['a','b','c']
pipeline
{
  agent any
  stages
  {
    stage('Build')
    {
       steps 
       {
        echo 'Test Jenkins File'
        script 
        {
          buildSOA([soaAppPath:'test', soaAppName: 'app name', soaProjName: 'proj name', appsList: appsList])
        }
       }
    }
  }
}
