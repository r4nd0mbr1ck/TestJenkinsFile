@Library('test')_

pipeline
{
  agent any
  stages
  {
    stage('Build')
    {
       steps 
       {
        script 
        {
          buildSOA([soaAppPath:'test', soaAppName: 'app name', soaProjName: 'proj name'])
        }
       }
    }
  }
}
