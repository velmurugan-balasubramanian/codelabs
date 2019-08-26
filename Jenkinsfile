node {
  def go = tool 'go'
  def GO_VERSION = go1.12.9.src.tar.gz
  try {
    sh 'echo $PATH'
    sh 'echo $GO_VERSION'
    sh 'curl -O https://dl.google.com/go/go1.12.9.src.tar.gz'
    sh 'echo working'
    sh 'curl --version'
    sh 'pwd'
    sh 'go version'
  }
  catch(any){

  }
  finally{

  }
}
