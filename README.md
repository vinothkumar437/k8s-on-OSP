# Kubernetes v1.16.3 deployment on the OpenStack 13

Vinothkumar P<br>
Email ID: vinothkumarpcse@gmail.com<br>
Bangalore, Karnataka, India.<br>

<h3>What is OpenStack ?</h3>
<p>OpenStack software controls large pools of compute, storage, and networking resources throughout a datacenter, managed through a dashboard or via the OpenStack API. OpenStack works with popular enterprise and open source technologies making it ideal for heterogeneous infrastructure.</p>
<h3>What is Kubernetes ?</h3>
<p>Kubernetes (K8s) is an open-source system for automating deployment, scaling, and management of containerized applications.</p>
<p>It groups containers that make up an application into logical units for easy management and discovery.</p>

<h3>Deploying Kubernetes on OpenStack</h3>
<p>Once you have OpenStack environment configured, deploying k8s will be done using a simple three steps phased approach.</p>

<li><b>Step 1:</b> Pre-requisites for the Bastion Node Setup.</li>
<li><b>Step 2:</b> Deploy k8s Infrastructure using Heat, Install and Configure the k8s using Ansible.</li>
<li><b>Step 3:</b> Accessing k8s dashboard.</li>

<h3>Step 1: Pre-requisites for the Bastion Node Setup</h3>
<ol>
  <li>OpenStack connectivity from the Bastion Node. Tested on OpenStack 13 (Queens).</li>
  <li>Install the Ansible 2.8.x on the Bastion Node.</li>
</ol>
