pipeline {
	agent any

	stages {
		stage('Build') {
			steps {
				echo 'Building ...'
				sh 'cp /var/lib/jenkins/workspace/First_Pipeline_feature_1-env/composer.phar /var/lib/jenkins/workspace/First_Pipeline_feature_1-env/composer'
				sh '/var/lib/jenkins/workspace/First_Pipeline_feature_1-env/composer update'
			}
		}
		stage('Test') {
			steps {
				echo 'Testing ...'
			}
		}
		stage('Deploy') {
			steps {
				echo 'Deploying'
			}
		}
	}
}

