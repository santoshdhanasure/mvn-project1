node{
	stage "Check out from git"
	
		echo "Checking out code"
		checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/santoshdhanasure/mvn-project1.git']]])

}
