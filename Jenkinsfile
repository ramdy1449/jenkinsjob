pipeline {
	agent any 
		stages{
			stage('1-s1'){
				steps{
					sh 'cat /etc/passwd'
					sh 'whoami'
				}
			}
			stage('2-s2'){
				steps{
					sh 'lscpu'
					sh 'whoami'
				}
			}
			stage('3-s3'){
				steps{
					sh 'df -h'
					sh 'touch test1'
				}
			}
			stage('4-s4'){
				steps{
					sh 'pwd'
					sh 'du -h'
				}

			}
			stage('5-s5'){
				steps{
					echo "welcome to randys first jenkins"
				}
			}
			stage('6-s6'){
				steps{
					sh 'bash -x /var/lib/jenkins/workspace/testing/scriptdemo.sh'
				}
			}
			
		}
}
