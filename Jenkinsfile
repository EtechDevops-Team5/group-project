ipeline{
	agent any 
	stages{
		stage('1-clone'){
			steps{
				checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'git-id', url: 'https://github.com/EtechDevops-Team5/group-project.git']])
			}
		}
		stage('2-Gerald'){
			steps{
				sh 'echo "team5group3 member"'
			}
		}
		stage('3-Pretei'){
			steps{
				sh 'echo "team5group3 member"'
			}
		}
		stage('4-Benoit'){
			steps{
				sh 'echo "team5group3 member"'
			}
		}
		stage('5-Henry'){
			steps{
				sh 'echo "team5group3 member"'
			}
		}
		stage('6-Olisa'){
			steps{
				sh 'echo "team5group3 member"'
			}
		}
		stage('7-Odile'){
			steps{
				sh 'echo "team5group3 member"'
			}
		}
		stage('2-systemscheck'){
			steps{
				sh 'sudo systemctl status jenkins'
				sh 'ps -ef'
			}	
		}
	}
}

