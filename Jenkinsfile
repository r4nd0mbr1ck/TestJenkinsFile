@Library('test')_

pipeline
{
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
