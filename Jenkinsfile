node {
  def go = tool 'go'
  def go_ver = 'go1.12.9.src.tar.gz'
  try {
    sh 'echo $PATH'
    sh 'echo $go_ver'
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
