// Powered by Infostretch 

timestamps {

node () {

	stage ('odoo - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/13.0']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'github credentials', url: 'https://github.com/vpolice3/odoo.git']]]) 
	}
}
}