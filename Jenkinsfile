node {
  
stage('checkout') {
 git branch: 'master', credentialsId: 'github_login', url: 'https://github.com/Pocaccount1/K8S_Playbooks.git'   
 }

stage('k8s deploy') {
   sh "ls"
   sh "ansible-playbook use_k8s_cluster_roles.yml"
    }
}
