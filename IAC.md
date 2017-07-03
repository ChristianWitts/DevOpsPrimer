Table of Contents
=================

* [Infrastructure as Code](#infrastructure-as-code)
  * [Packer](#packer)
  * [Terraform](#terraform)
  * [Ansible](#ansible)
  * [Chef](#chef)
  * [Puppet](#puppet)
  * [Salt](#salt)
  * [StackStorm](#stackstorm)

## Infrastructure as Code

Infrastructure as code is the process of managing and provisioning computer data centers through machine-readable definition files, rather than physical hardware configuration or interactive configuration tools.

- [Baking Delicious Cloud Instances](https://blog.kintoandar.com/2017/06/Baking-delicious-cloud-instances.html)

### Packer

[Packer](https://www.packer.io/) is a free and open source tool for creating golden images for multiple platforms from a single source configuration. Packer is lightweight, runs on every major operating system, and is highly performant, creating machine images for multiple platforms in parallel. Packer does not replace configuration management like Chef or Puppet. In fact, when building images, Packer is able to use tools like Chef or Puppet to install software onto the image.

A machine image is a single static unit that contains a pre-configured operating system and installed software which is used to quickly create new running machines. Machine image formats change for each platform. Some examples include AMIs for EC2, VMDK/VMX files for VMware, OVF exports for VirtualBox, etc.

- [The Packer Book - James Turnbull](https://packerbook.com/)
- [Documentation](https://www.packer.io/docs/index.html)
- [Using Packer and Ansible to Build Immutable Infrastructure](https://blog.codeship.com/packer-ansible/)
- [Packer – automating virtual machine image creation](http://alexconst.net/2016/01/11/packer/)
- [Automated Image Builds with Jenkins, Packer, and Kubernetes](https://cloud.google.com/solutions/automated-build-images-with-jenkins-kubernetes)

### Terraform

[Terraform](https://www.terraform.io/) enables you to safely and predictably create, change, and improve production infrastructure. It is an open source tool that codifies APIs into declarative configuration files that can be shared amongst team members, treated as code, edited, reviewed, and versioned.

Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently. Terraform can manage existing and popular service providers as well as custom in-house solutions.

Configuration files describe to Terraform the components needed to run a single application or your entire datacenter. Terraform generates an execution plan describing what it will do to reach the desired state, and then executes it to build the described infrastructure. As the configuration changes, Terraform is able to determine what changed and create incremental execution plans which can be applied.

The infrastructure Terraform can manage includes low-level components such as compute instances, storage, and networking, as well as high-level components such as DNS entries, SaaS features, etc.

- [Terraform: Up & Running](http://www.terraformupandrunning.com/)
- [Documentation](https://www.terraform.io/docs/index.html)
- [Terraform for Bare Metal with Matchbox](https://coreos.com/blog/matchbox-with-terraform)
- [Terraform Version Manager](https://github.com/kamatama41/tfenv)
- [Terraform Gotchas And How We Work Around Them](https://blog.heapanalytics.com/terraform-gotchas/)
- [Using Terraform to manage Google Cloud Platform infrastructure as code](https://cloudplatform.googleblog.com/2017/04/guest-post-using-Terraform-to-manage-Google-Cloud-Platform-infrastructure-as-code.html)
- [Why we use Terraform and not Chef, Puppet, Ansible, SaltStack, or CloudFormation](https://blog.gruntwork.io/why-we-use-terraform-and-not-chef-puppet-ansible-saltstack-or-cloudformation-7989dad2865c)
- [Terraform in Google Compute Made Easy](https://sweetcode.io/terraform-google-compute-made-easy/)
- [Provision a Cluster on Google Cloud with Terraform](https://lincolnloop.com/blog/provision-cluster-google-cloud-terraform/)

### Ansible

[Ansible](https://www.ansible.com/) is an open-source automation engine that automates software provisioning, configuration management, and application deployment.

- [Ansible Up & Running](https://www.ansible.com/ansible-book)
- [Ansible for DevOps](https://leanpub.com/ansible-for-devops)
- [Documentation](http://docs.ansible.com/)
- [Automation with Ansible](https://medium.com/@alonisser/automation-with-ansible-50ad4b9ab919)
- [Writing Ansible Modules, Complete with Tests](https://www.pluralsight.com/guides/python/writing-ansible-modules-complete-with-tests)
- [19 Minutes with Ansible - Part 1/4](https://sysadmincasts.com/episodes/43-19-minutes-with-ansible-part-1-4)
- [Learning Ansible with Vagrant - Part 2/4](https://sysadmincasts.com/episodes/45-learning-ansible-with-vagrant-part-2-4)
- [Configuration Management with Ansible - Part 3/4](https://sysadmincasts.com/episodes/46-configuration-management-with-ansible-part-3-4)
- [Zero-downtime Deployments with Ansible - Part 4/4](https://sysadmincasts.com/episodes/47-zero-downtime-deployments-with-ansible-part-4-4)
- [Ansible vs Salt vs StackStorm](https://medium.com/@anthonypjshaw/ansible-v-s-salt-saltstack-v-s-stackstorm-3d8f57149368)

### Chef

[Chef](https://www.chef.io/) is an automation platform for DevOps.

- [Learning Chef - A Guide to Configuration Management & Automation](http://shop.oreilly.com/product/0636920032397.do)
- [Documentation](https://docs.chef.io/)
- [Supermarket - Cookbook Search](https://supermarket.chef.io/)
- [Learn Chef - Tutorials](https://learn.chef.io/#/)

### Puppet

### Salt

### StackStorm

[StackStorm](https://stackstorm.com/) is event-driven automation commonly used for auto-remediation, security responses, facilitated troubleshooting, complex deployments, and more. Includes rules engine, workflow, 1800+ integrations (see /st2contrib), native ChatOps and so forth.

When failures happen, StackStorm can act as Tier 1 support: It troubleshoots, fixes known problems, and escalates to humans when needed. Be it a silly yet common “when disk is out of space, clean up the logs”, recovering RabbitMQ split-brain, migrating MySQL master, or automating troubleshooting guides for OpenStack or Cassandra… the learning from Facebook, LinkedIn and others is: if you don’t automate, you die.

- [StackStorm GitHub](https://github.com/StackStorm/st2)
- [StackStorm Exchange](https://exchange.stackstorm.org/)
- [Documentation](https://docs.stackstorm.com/index.html)
