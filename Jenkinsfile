node{
	stage "Check out from git"
	
	echo "Checking out code"
	
	checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'D:\\devps\\projects\\mavan']]])

}
