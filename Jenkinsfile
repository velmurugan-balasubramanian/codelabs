node {
  def go = tool 'go'
  try {
    sh 'echo $PATH'
    sh 'echo ${GO_VERSION}'
    sh 'curl -o go.tar.gz https://dl.google.com/go/go1.12.9.src.tar.gz'
    sh 'pwd'
    sh 'cd ../..'
    sh 'pwd'
    sh 'tar -zxf go.tar.gz'
    sh 'echo working'
    sh 'curl --version'
    sh 'go version'
  }
  catch(any){

  }
  finally{

  }
}
