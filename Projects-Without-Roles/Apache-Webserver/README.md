# Making Webserver Service Restart Idempotent!
* By Default, Restarting the webserver service is not idempotent & it impacts the performance of the system if everytime the Ansible playbook runs & it restarts the Webserver Service.

* If only "started" is used as the service state, then if anything is updated in the webpage, then it will not b updated until the service is restarted, therefore it is necessary to restart the service as soon as something is updated.

* The solution for this problem is to use "Handler" in Ansible, that is whenever there occur some changes in the Webpage, only then the service of the Webserver will be restarted, otherwise service will not be changed because it works on idempotence when "service = started" is used.

* In this code, the same is implemented for making the Webserver service restart idempotent!