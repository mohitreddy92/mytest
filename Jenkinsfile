// Powered by Infostretch 

timestamps {

node () {

	stage ('dash - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'GitHub', url: 'https://github.com/mohitreddy92/mytest.git']]]) 
	}
	stage ('dash - Build') {
 			// Shell build step
sh """ 
echo "hello world" 
 """
// Unable to convert a build step referring to "org.jenkinsci.plugins.conditionalbuildstep.ConditionalBuilder". Please verify and convert manually if required. 
	}
}
}