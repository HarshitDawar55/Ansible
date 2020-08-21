![Ansible](Images/ansible.png)

# Ansbile

:sparkles::fireworks::tada: Important points about this Repository!!!!! :tada::fireworks::sparkles:

- This Repository will act as a complete Guide for Ansible, explaining each concept of Ansible with their practical code scripts written in YAML Language!

- For brief introduction of Ansible please refer to the section given below!

# What is Ansible?

- It is an **Automation Tool** & also the best automation tool available in the market.

- It is the most demanding tool in the market right now.

- It is used for **configuration management**.
  * To explain its use in detail, consider an environment in which we have machine of heterogenous system (OS) installed in them, to configure them manually i.e. to install some packages, or to perform some changes in the system manually is not possible practically, if we have a very large set-up (practical scenario in most of the companies). 

  * Therefore to perform configuration automatically, Ansible is required. Although there are other competitors of Ansible in the market like Puppet & Chef, but Ansible is more powerful and mature product.

  * Ansible works on different mechanism i.e. **Push Mechanism** while Puppet & Chef works on **Pull Mechanism** which has multiple advantages for Ansbile.

  * It is a **Agentless tool**.
  
  * It supports **Ad-hoc commands & Script(Playbooks)**.


# How to download Ansible?
- In order to download the Ansible software:
  * As it is **written in python**, so, it can be downloaded using the package manager of Python i.e. **pip**.
  * Based on your python version, run the command **"pip3 install ansible"**.

# How to run Ansible Playbook?
- To run Ansible Playbook, run the command **"ansible-playbook" < path to the playbook >**.

- Ansible code can only be written in YAML Language.

# Best/Good Practices for Code Management in Ansible!
  * Code Management is very crucial thing in the Industry, because there projects are very big, that involves huge code, therefore proper management leads to ease of everything.

  * To Manage Code, Ansible provide one functionality named **Roles**.
    * A **Role** can be understood as a complete package with proper directory structure and file arrangement. 

    * Name which is according to the need of the Role is assigned to that role, & the same code can be sent to anyone in the world & can be executed in just one command, by just entering the host which needs to be configured using that role.

    * Also, variables defined in the Role Directory can be **changed at the run time very easily**.

# How to craete an Ansible Role?
* To create an Ansible Role we need to run the command, **"ansible-galaxy init 'rolename'"**.

* By default Ansible reads the roles from 3 directories, if the created role is not present in any of those by-default directory, then it will not be executed.



# License of this Repository!
To check out the License for this Repository please click [here!](LICENSE)
