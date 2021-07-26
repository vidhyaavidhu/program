 pipeline{
  agent any
  stages{
    stage(checkout)
    {
     steps{
        sh """
              javac simple.java
              java simple
              """
              }
              }
              stage(build)
              {
                steps{
                  echo "hello"
                  }
                  }
                  }
                  }    
        
        
