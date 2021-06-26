node('aks') {
    stage('checkout') {
    	checkout scm()
    }
    stage('gradle'){
	sh "gradle wrapper"
    }
}
