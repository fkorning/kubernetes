═══════════════════════════════════════════════════════════════════════
# Kubernetes
═══════════════════════════════════════════════════════════════════════


<code> 

	#=============================================================================#
	# Manufakture Kubernetes Cluster
	#-----------------------------------------------------------------------------#

                                  _____        __      __                        
      _____ _____    ____  __ ___/ ____\____  |  | ___/  |_ __ _________   ____  
     /     \\__  \  /    \|  |  \   __\\__  \ |  |/ /\   __\  |  \_  __ \_/ __ \ 
    |  Y Y  \/ __ \|   |  \  |  /|  |   / __ \|    <  |  | |  |  /|  | \/\  ___/ 
    |__|_|  (____  /___|  /____/ |__|  (____  /__|_ \ |__| |____/ |__|    \___  >
          \/     \/     \/                  \/     \/                         \/ 


	#-----------------------------------------------------------------------------#
	# (c) Francis Korning 2024.
	#=============================================================================#
 	                                                                              
</code>		
	

Manufakture is a lightweight Cloud and Cluster dev box with a full Windows POSIX environment.

It consists: of Syswin, Cygwin, VirtualBox, Vagrant, Docker (Toolbox), Kubernetes (Minikube).

And then a slew of other Development SDKs and tools (Puppet, Perl, Ruby, Python, Java, etc).

This is the Kubernetes bit.

	

# Kubernetes provisioner


At minimum we want the kubernetes-cli client and a local MiniKube cluster controller.

We will also want to support common kubectl-plugins via krew (or from jordanwilson230).

We will need a number of json/yml/yq parsing and inspection utilities.

We will also probably want kops, helm, and terraform.


───────────────────────────────────────────────────────────────────────
## Preqequisites
───────────────────────────────────────────────────────────────────────

* Make sure you have a *Manufacture* SysWin and CygWin full POSIX system running and installed.

	https://sourceforge.net/p/manufacture/syswin/

	https://sourceforge.net/p/manufacture/cygwin/

Manufacture provides the "su.exe" command to run administrator shells (instead of powershell).

* In addition to cygwin, you'll probably have a separate gitbash (installed by DockerToolBox).


* Minikube is itself a docker container, which means you need Docker, which means you need:

	https://github.com/fkorning/virtualbox
	
	https://github.com/fkorning/vagrant

	https://github.com/fkorning/docker




───────────────────────────────────────────────────────────────────────
# Minikube Cloud (local cluster)
───────────────────────────────────────────────────────────────────────


───────────────────────────────────────────────────────────────────────
# Kubernetes Client (kube-cli)
───────────────────────────────────────────────────────────────────────


───────────────────────────────────────────────────────────────────────
# Kubernetes Tools (misc tools)
───────────────────────────────────────────────────────────────────────


───────────────────────────────────────────────────────────────────────
# Kubernetes Ops (kops)
───────────────────────────────────────────────────────────────────────


───────────────────────────────────────────────────────────────────────
# Kubernetes Helm (Navigator)
───────────────────────────────────────────────────────────────────────
	
───────────────────────────────────────────────────────────────────────
# Terraform Cloud (Cloud Formation)
───────────────────────────────────────────────────────────────────────
	
═══════════════════════════════════════════════════════════════════════
# (c) Francis Korning 2024.
═══════════════════════════════════════════════════════════════════════
