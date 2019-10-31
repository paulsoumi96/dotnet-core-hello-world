node{

stage('Checkout') { 
	  git url: 'https://github.com/paulsoumi96/dotnet-core-hello-world', branch: 'master'
   }
stage('Restore PACKAGES') {
    bat "dotnet restore --configfile NuGet.Config"
  }
  stage('Clean') {
    bat 'dotnet clean'
  }
}
