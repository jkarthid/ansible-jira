# ansible-jira
Liatrio's JIRA Playbook

Handles Java, Postgres, Nginx, JIRA. Only does initial install of JIRA - requires manual configuration via UI post-install.

When running, pass in `postgresql_jira_password`:

    ansible-playbook -u ec2-user --extra-vars "postgresql_jira_password=***********" jira.yml

## Hackathon Pipeline
 - [hackathon-pipeline-terraform](https://github.com/liatrio/hackathon-pipeline-terraform)
 - [ansible-jenkins](https://github.com/liatrio/ansible-jenkins)
 - [anisble-jenkins-agents](https://github.com/liatrio/ansible-jenkins-agents)
 - [ansible-artifactory](https://github.com/liatrio/ansible-artifactory)
 - [ansible-jira](https://github.com/liatrio/ansible-jira)
 - [ansible-bitbucket](https://github.com/liatrio/ansible-bitbucket)
 - [ansible-confluence](https://github.com/liatrio/ansible-confluence)
 - [ansible-sonarqube](https://github.com/liatrio/ansible-sonarqube)
 
